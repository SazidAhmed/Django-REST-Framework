# Django-RESTApis
Simple Todo app with Django Rest Framework


Installation:

$ pip install virtualenv

$ virtualenv venv

$ cd venv

$ source Scripts/activate

$ cd Django-REST-Framework

$ pip install django

$ pip install djangorestframework

$ cd djangoRest

$ python manage.py makemigrations

$ python manage.py migrate

$ python manage.py createsuperuser

$ py manage.py runserver

-------------------Follow these steps if you're creating a brand new django project--------------------------------

$ pip install virtualenv

$ virtualenv venv

$ cd venv

$ source Scripts/activate

$ pip install django

$ django-admin startproject djangoRest

$ cd djangoRest

$ python manage.py startapp apis

$ python manage.py makemigrations

$ python manage.py migrate

$ python manage.py createsuperuser


Install Django Rest Framework:

cd venv

$ pip install djangorestframework


Open settings.py and in Installed app add these lines

'apis.apps.ApisConfig',

'rest_framework',

All set ... Have fun . . . 
