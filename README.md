create folder `mkdir django-things`

install virtual environment `python3.11 -m venv .venv`

`source .venv/bin/activate`

`pip install django`

`django-admin startproject django_things_project .` 

(command, name of project, period will install it into the folder(otherwise double folders)) 

`tree`

`python manage.py migrate`

`settings.py` all boilerplate in Django, configuration constants

`python manage.py runserver`

check the port, quit the serve with control c, before installing the updates

refresh to see the tables, apply and hit okay w/in db.sqlite3

stop webserver

`python manage.py startapp things` command startapp, argument things

`tree`

add the string things to `settings.py` `INSTALLED_APPS = [
'things'
]`

Now the project knows about the app. You can start working on your app

start in `views.py` with the TemplateView module

next create `urls.py`

this is where the routes will be

now update the `urls.py` inside of the project, including everything inside yourprojectname.url in the app

adds template folder, add `base.html` and `home.html`

emment character in `base.html` and then add in the block/end block

in home.html add in extends

be sure to add your relative path name to templates directory inside the lists, `BASE_DIR/'templates'`

##### Tailwind

`python -m pip install django-compressor`

add it to installed apps in `settings.py` as a string 'compressor'

`npm install -D tailwindcss`

`npx tailwindcss init`

creates the config file tailwind.config.js

make sure `node_modules` is in .gitignore

`npx tailwindcss -i ./static/src/input.css -o ./static/src/input.css --watch`

`npm install flowbite`

server and tailwindcss watch need to be running in separate tabs

inside the app, `tests.py`

`from django.urls import reverse`

`from djano.test import SimpleTestCase`

run via `python manage.py test`

