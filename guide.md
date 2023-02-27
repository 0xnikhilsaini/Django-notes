# Djanog
## Build CRUD API with Django REST framework


## setup project
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- python manage.py migrate
- python manage.py runserver




## setup djanog

- mkdir Django_Crud_Project
cd Django_Crud_Project && code .

- python3 -m venv venv
- source venv/bin/activate
- pip install django djangorestframework

- django-admin startproject notes .

- python manage.py migrate

- python manage.py runserver
- django-admin startapp note_api


## add 
   'note_api',
    'rest_framework'
    
    in Installed_app array
    
- create djanog model
- create model serializer
- now work on view file

- work on url.py in app


- work on url.py in project 


## setup cors 
- pip install django-cors-headers
- add   'corsheaders', in apps

- add in midlleware 
-  'corsheaders.middleware.CorsMiddleware',
    'django.middleware.common.CommonMiddleware',

- add in setting.py 

 CORS_ALLOWED_ORIGINS = [
    "http://localhost:3000"
]
CORS_ALLOW_CREDENTIALS = True


- run  - python manage.py migrate

- run - python manage.py runserver



