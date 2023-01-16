# Profiles REST API

Profiles REST API course code.

# To create python virtual environment and activate
base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % python -m venv ~/env
(base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % source ~/env/bin/activate

# To deactivate 
(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % deactivate 
(base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % 

# To install dependecy
(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % ls
LICENSE                 README.md               requirements.txt
(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % pip install -r requirements.txt 

# To start a django project
(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % django-admin.py startproject profiles_project .

# To start a django app
(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % python manage.py startapp profiles_api

# To run the project 

(env) (base) ayushkumar@Ayushs-MacBook-Air profile-rest-api % python manage.py runserver 0.0.0.0:8000
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 19 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, authtoken, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.

January 16, 2023 - 07:12:28
Django version 2.2, using settings 'profiles_project.settings'
Starting development server at http://0.0.0.0:8000/
Quit the server with CONTROL-C.

