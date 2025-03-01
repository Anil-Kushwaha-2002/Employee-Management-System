# Employee Management System

A **role-based Employee Management System** built with **Python** and **Django**, enabling efficient tracking and management of employee data.

## Features

- ✅ **Role-Based Access Control**: Admins have full access while maintaining data security.
- ✅ **CRUD Operations**: Add, View, Update, and Delete employee records.
- ✅ **Responsive Design**: Works seamlessly on both mobile and desktop platforms.
- ✅ **Django Framework**: Utilizes Django for robust backend development.

---

## Installation & Setup

Run the following commands step by step to set up the Django project:

```bash
# Install Django
pip install django

# Check Django Version
python -m django --version

# Check all installed modules and versions
pip freeze

# Create a new Django Project
django-admin startproject nitman

# Navigate into the project directory
cd nitman

# Create a new Django App
python manage.py startapp nitapp

# Apply initial migrations
python manage.py migrate

# Create a superuser (admin)
python manage.py createsuperuser

# Run the Django development server (default port 8000)
python manage.py runserver

# Run the server on a different port (example: 8080)
python manage.py runserver 8080

# Run the server on a specific IP and port
python manage.py runserver 0.0.0.0:8000


## Command 
# Command To Install Django:-
pip install django

# Command To Check Django Version:-
python -m django --version

# Command To Check all the versions of installed modules:-
pip freeze

##  Command To Create A Project & An App In Django

# Command To Create A Project:-
django-admin startproject nitman

# Command To Create An App:-
python manage.py startapp nitapp

# where nitman is project name & nitapp is app name


##  Command To Run A Project In Django
# Command To Run A Project:-
python manage.py runserver

By default, this command starts the development server on the internal IP at port 8000.

If you want to change the server's port, pass it as a command-line argument.

For instance, this command starts the server on port 8080:-

python manage.py runserver 8080

If you want to change the server's IP, pass it along with the port, use:-

python manage.py runserver 0.0.0.0:8000

```bash
