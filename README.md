# Django-WebApp       

CS50 Web Programming Final Project- Website to upload files and download shared files from other users.

<h4>Part 1:</h4>
<ol>
    <li>Create a web-app where a user can login.</li>
    <li>User can upload files.</li>
    <li>User can view his/her uploaded files.</li>
</ol>

<h4>Part 2:</h4>
<ol>
     <li>User can search and view profile of other users.</li>
     <li>They can share their uploaded files with any of those users.</li>
     <li>Users can see the shared files by other users also in uploaded files.</li>
</ol>

<h4>Additional Features:</h4>
<ol>
    <li>In users profile user can set his/her profile picture.</li>
    <li>Users can download other users uploaded files.</li>
    <li>The user can upload any type of files such as images, videos, text files and also different types of programs like python code, java code, etc.</li>
</ol>
    
<h2>Technologies Used:</h2>
<ul>
    <li>Python</li>
    <li>Django</li>
    <li>Bootstrap</li>
    <li>JavaScript</li>
</ul>
    
<h2>Additional Python Modules Required:</h2>
<ul>
    <li>Django</li>
    <li>django-crispy-forms</li>
    <li>Pillow</li>
</ul>
  

<h2>Usage :</h2>

    python django_web_app/manage.py makemigrations

    python django_web_app/manage.py migrate

    python django_web_app/manage.py runserver
    
   In your web browser enter the address : http://localhost:8000 or http://127.0.0.1:8000/
  
<h2> Files & Directories</h2>

- `Main Directory`

  - `django_web_app` - Main application directory.

    - `users` - Profile app for maintaining user's profile
      - `models.py` - ORM profile model.Contains an class Profile which has all information of user.
      - `forms.py` - Contains classes UserRegistrationForm, UserUpdateForm and ProfileUpdateForm.
      - `views.py` - Contains all view functions for profile, like view, update,registraion,delete etc.

    - `django_web` - Authentication app.
      - `urls.py` - Contains all url paths for authentication, like login, register profile and logout.
      
    - `blog` - Core app for all functionalities like create,search, update, delete posts etc.
      - `models.py` - Contains class Post which has all information about the creating, searching, updating and deleting posts.
      - `urls.py` - Contains all url paths for posts, like view dashboard,creating, searching, updating and deleteing posts.
      - `views.py` - Contains all view functions for posts, like dashboard,creating, searching, updating and deleteing posts.
       
     - `media` - contains sample pictures, videos, mp3 files to test the website.
     - `manage.py` - command line utility that lets you interact with the Django project in varous ways.
     - `db.sqlite3` - default database to store project directory.
    - `static` - Holds all static files.
      - `main.css` - Contain all css files for styling the website.
      - `main.js` - Contains all JavaScript files for image manipulation functionalities.
      - `img` - Holds all static images and icons.
    - `Templates` - Holds all html files.

<h2> Justification</h2>


This project is distinct from all previous projects so far. Why?
<ul>
    <li>Feature to upload any file text,image,mp3 or video</li>
    <li>Dahboard to show uploaded files</li>
    <li>View files of people you follow</li>
    <li>Feature to download any type of file like text, image, video, mp3 from other's profile</li>
    <li>Completely Mobile responsive.</li>
</ul>

# Working:
The video link is given below
https://youtu.be/Z2dWQtDBqC8



