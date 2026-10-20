# TaskFlow — Django Task Manager

**Assignment 15 | Group Aphrodite**

TaskFlow is a web-based task management application developed using Python and Django. It helps users organize tasks, set priorities and due dates, and track task completion.

## Group Members

- Ariba Mayeesha
- Ifty Fardin
- Mahtab Iram
- Nizam Sabiha

## Features

- Create new tasks
- View the task list and task details
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Set task priorities and due dates
- Search and filter tasks
- View task statistics on the dashboard
- Manage task records through Django Admin

## Technologies Used

- **Python** — application logic
- **Django** — web framework and backend
- **HTML and CSS** — user interface
- **SQLite** — database
- **GitHub** — version control and project hosting

## Project Structure

```text
aphrodite-django-task-manager/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── ...
└── taskmanager/
    ├── models.py
    ├── views.py
    ├── forms.py
    ├── admin.py
    ├── urls.py
    ├── migrations/
    └── templates/
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Arilala20/aphrodite-django-task-manager.git
cd aphrodite-django-task-manager
```

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Apply database migrations

```bash
python manage.py migrate
```

### 4. Create an administrator account (optional)

```bash
python manage.py createsuperuser
```

Follow the prompts to create your username and password.

### 5. Start the development server

```bash
python manage.py runserver
```

Open the application at:

http://127.0.0.1:8000/

Django Admin is available at:

http://127.0.0.1:8000/admin/

## Testing

The application was tested locally. The main features tested include:

- Creating tasks
- Editing task details
- Marking tasks as completed
- Deleting tasks
- Viewing and managing tasks through Django Admin

## Screenshots

