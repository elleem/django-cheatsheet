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

add the name things to INSTALLED_APPS = [
'things'
]


