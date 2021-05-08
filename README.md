# todoapp
A simple django todoapp

## Python
### Version 3.7

## Install pipenv
### Generate virtualenv
    pipenv --python 3.7.7

### Access to venv
    pipenv shell

### Install packages from .txt file
    pipenv install

### Generate DB
* Active venv
* Move to root folder
* Type: python manage.py makemigrations
* Type: python manage.py migrate

### Run project
    python manage.py runserver --noreload