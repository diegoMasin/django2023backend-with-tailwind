# django2023backend-with-tailwind

Criando projeto Django do zero

### Steps before first commit

Create your venv

> python -m venv nome-da-venv (Create folder outside the project)

Active your venv

> folder-venv/Scripts/activate

Install the dependencies

> pip install django python-decouple django-extensions

Create a repository and copy it for begin django installation; Go into the folder

Get the django version with pip freeze and othe things

Create a file requirements.txt and paste into:
_Django==4.1.6_;
_django-extensions==3.2.1_;
_python-decouple==3.7_

Add to:
_requests==2.28.1_

In terminal make it below:

> django-admin startproject backend .

Go in backend folder and make it below:

> python ../manage.py startapp core

Get a django gitignore file and create the same file here (eg: https://github.com/rg3915/dicas-de-django/blob/main/.gitignore)

Generate a .env file; Using command _python gen_env.py_ into project folder (using this file: https://github.com/rg3915/dicas-de-django/blob/main/contrib/env_gen.py)

Into backend folde on settings.py, add import decouple

Update with "config" the lines:
SECRET_KEY;
DEBUG;
ALLOWED_HOSTS
