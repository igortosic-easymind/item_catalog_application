# Item Catalog Application

Modern web applications perform a variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data. The CRUD is fundamentals of every web application. In this instance, you have the simple web application with registration form and list of items as well as provide a user registration.

## Installing

1. Using Command Prompt or Node install `virtualenv venv` to your created folder and       start it with `.\venv\Scripts\activate.bat`
2. install Django `pip install Django==1.11.6`
3. mkdir src && cd src
4. git init
5. git clone https://github.com/igortosic-easymind/item_catalog_application.git
6. cd item_catalog_application
7. `python manage.py runserver` <port>

You might install `pip install Pillow` after you start the server

## Default user is:
    user: admin
    password: administrator

## Notes:
Also, you can create superuser with `python manage.py createsuperuser` from Command Prompt.

Default local server is: http://127.0.0.1:8000

Manage your products from: http://127.0.0.1:8000/admin/
