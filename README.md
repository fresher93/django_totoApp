# todoapp
A simple django todoapp

## Generate virtualenv
* On Windows 10 OS
    * Open cmd/powershell
    * Type: python -m venv project_path\venv_folder_name
* ON Ubuntu/MacOS
    * Open terminal/iterm
    * Type: python3 -m venv project_path\venv_folder_name
* Change version python if you want on venv_folder_name\pyvenv.cfg
## Active venv and install packages
* On Windows 10 OS
    * cd to venv_folder_name\Scripts
    * activate
* ON Ubuntu/MacOS
    * active venv_folder_name\Scripts
* Move back to root folder
* Type: easy_install -U pip==20.2.4
* Type: easy_install -U setuptools=50.3.2
* Type: pip install -r requirements.txt
## Generate DB
* Active venv
* Move to root folder
* Type: python manage.py makemigrations
* Type: python manage.py migrate
## Run project
* Active venv
* Move to root folder
* Type: python manage.py runserver
