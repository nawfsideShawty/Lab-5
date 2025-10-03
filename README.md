# Lab-5

REF 1 – Installing Framework
The Framework we used was Django
-	We created a directory called MyProject
- mkdir MyProject


-	We created a virtual environment :
- python3 -m venv venv
- source venv/bin/activate
- pip install Django


-	We created a new Django Project
- Django-admin startproject myproject .
- Python manage.py startapp core
- http://127.0.0.1:8000/

-	We then started the server and created a superuser
- python manage.py migrate
- python manage.py runserver
- python manage.py createsuperuser
- http://127.0.0.1:8000/admin
