# PofP
Prince of Pauper website

## Description
This project is intended to create a simple site for Magic: The Gathering content centered on the pauper format.
Currently the site has a home page and a page for articles which also includes functionality for comments.
Their is user account registration and login supported by Django included, necessary for making comments.

## Requirements
1. Django - https://www.djangoproject.com/download/
2. Python 3 - https://www.python.org/downloads/

## Installation
1. Download all files to a folder on your PC.
2. I suggest creating a virtual environment to work on this. To do this:
   1. In windows command line run the command "python -m pip install pip"
   2. Then use the commands "pip install virtualenv" followed by "pip install virtualenvwrapper-win"
   3. You can now enter "mkvirtualenv [name of your virtual environment]" to create a virtual environment
     You can now use the command "workon [name of your virtual environment]" to begin working in the virtual environment.
3. In order for the site to run correctly you will need to make migrations for the 'blog' app which handles articles and comments.
  to do this:
   1. In command prompt use the command "cd [filepath for the directory you downloaded this project to]" to select the project directory.
      (make sure you are working in your virtual environment at this point)
   2. Run the following commands:
      1. python manage.py migrate
      2. python manage.py makemigrations blog
      3. 
      
### WIP
