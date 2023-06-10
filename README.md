`python3.11 -m venv .venv`

`source .venv/bin/activate`

`mkdir django-things`

`pip install django`

`django-admin startproject django_things_project .` (period will install it into the folder) 

`tree`

settings.py all boilerplate in Django, configuration constants

`python manage.py runserver`

check the port, quit the serve with control c, before installing the updates

`python manage.py migrate`

refresh to see the tables, apply and hit okay w/in db.sqlite3

stop webserver

`python manage.py startapp things` command startapp, argument things

`tree`

add the string things to `settings.py` `INSTALLED_APPS = [
'things'
]`

start in `views.py`

`python -m pip install django-compressor`

add it to installed apps in `settings.py`

`npm install -D tailwindcss`

`npx tailwindcsss init`

creates the config file tailwind.config.js

make sure `node_modules` is in gitignore

`npx tailwindcss -i ./static/src/input.css -o ./static/src/input.css --watch`

`npm install flowbite`



