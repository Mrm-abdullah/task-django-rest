## Setup Instructions

1. Clone the repository.
2. Install dependencies:
   pip install -r requirements.txt

3. Run migrations:
    python manage.py makemigrations
    python manage.py migrate

4. Create a superuser:
    python manage.py createsuperuser

5. project run
    python manage.py runserver

6. api
    "users": "http://127.0.0.1:8000/api/users/",
    "projects": "http://127.0.0.1:8000/api/projects/",
    "project-members": "http://127.0.0.1:8000/api/project-members/",
    "tasks": "http://127.0.0.1:8000/api/tasks/",
    "comments": "http://127.0.0.1:8000/api/comments/"





