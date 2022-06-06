# To-Do-App
## A project that helps you to get familiar with Django.

### This project is based on Django version 4.0.4
**Steps to RUN:**

Step 1: Install Virtual Environment 
        - pip install virtualenv

Step 2: Create Virtual Environment inside project directory
        - python -m venv ./venv

Step 3: Activate the virtual environment
        - .\venv\Scripts\activate

Step 4: Create superuser (Admin for app management)
        - python manage.py createsuperuser

Step 5: Set Username and a Password, email can be ignored.

Step 6: Run server
        - python manage.py runserver

On the output screen you should see:

Starting development server at http://127.0.0.1:8000/

http://127.0.0.1:8000/admin [For Admin portal]
http://127.0.0.1:8000/todolist/ [For the App]