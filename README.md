# Google API tut
https://www.youtube.com/watch?v=_vCT42vDfgw

- check django official tutorial

Win installation
https://realpython.com/django-setup/

mkvirtualenv django_google_api
/ I have used stadard>
python -m venv django-google-api

\env\Scripts\activate.bat
activate.bat
- ak je dostupny requirements.txt
python -m pip install -r requirements.txt

pip install django
django-admin startproject django_google_api

--win zlo problem s path django, idem na ubuntu

UBUNTU-------------------------------------------------

-> gitignore files for django
https://github.com/django/django/blob/main/.gitignore

touch .gitignore

- https://linuxize.com/post/how-to-create-python-virtual-environments-on-ubuntu-18-04/

- sudo apt install python3-venv
- python3 -m venv django-google-api-env
- source django-google-api-env/bin/activate

- pip install django
- django-admin startproject django_google_api
- cd django_google_api

- python manage.py startapp main

install VS CODE
- sudo snap install --classic code

# setting.py
- use library Django decoupled to prevent exposure of secret key, removing sensitive informvation from project
- adda static routes to the content and API

# urls.py
     we are referencing urls.py that is in the main directory, so we have to create it
# /main/urls.py

- install request library