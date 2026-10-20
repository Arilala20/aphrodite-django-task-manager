# Aphrodite Task Manager — Django Web Application

A beginner-friendly Django task tracking app for HAMK Assignment 15, created for Group Aphrodite.

## Features
- Add, edit, complete, and delete tasks
- Task priority and status
- Due dates and descriptions
- Search/filter tasks
- Django admin interface for managing tasks
- Responsive HTML/CSS interface

## Requirements
- Python 3.10+
- pip

## Setup on Windows (PowerShell)

1. Extract the project ZIP and open the extracted folder in VS Code.
2. Open Terminal in that folder.
3. Create a virtual environment:

   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

4. Install dependencies:

   ```powershell
   pip install -r requirements.txt
   ```

5. Create the database tables:

   ```powershell
   python manage.py migrate
   ```

6. Create an admin account:

   ```powershell
   python manage.py createsuperuser
   ```

   Enter a username, email (optional), and password. Keep these private.

7. Start the website:

   ```powershell
   python manage.py runserver
   ```

8. Open http://127.0.0.1:8000/ in your browser.
9. Open http://127.0.0.1:8000/admin/ to test the Django admin interface.

## Project structure

```text
aphrodite_django_task_manager/
├── manage.py
├── requirements.txt
├── mysite/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
└── taskmanager/
    ├── migrations/
    │   └── __init__.py
    ├── templates/taskmanager/
    │   ├── base.html
    │   ├── task_list.html
    │   └── task_form.html
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── urls.py
    └── views.py
```

## AI assistance
ChatGPT assisted with drafting the Django project structure, model, admin configuration, form, views, templates, and setup instructions. Review and test the code before submitting.

## Assignment reflection
AI made it faster to scaffold the model, admin interface, views, and templates. The main learning steps were installing Django, running migrations, creating a superuser, and testing the app in the browser and admin panel.
