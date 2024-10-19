**To-Do List Maker App**

A simple and efficient web-based to-do list maker built using Django. This app allows users to create, manage, and organize tasks with an intuitive user interface. Users can add, edit, delete, and mark tasks as complete.

**Features**

1. User authentication (login and register)
2. Create, update, delete, and complete tasks
3. Filter tasks (e.g., view all tasks, completed tasks, pending tasks)
4. Responsive, mobile-friendly design
5. Technologies Used

Backend: Django (Python)

Database: SQLite (default Django database)

Frontend: HTML5, CSS, JavaScript


**Data Models**

Task Model
id: Integer, primary key
title: CharField, max_length=255
description: TextField (optional)
completed: BooleanField (default: False)
created_at: DateTimeField, auto_now_add=True
updated_at: DateTimeField, auto_now=True
User Model
Django's default User model is used for user authentication.

URL Routing
The app includes the following URL routes:

/ : Home page displaying all tasks.
/add/: Page to add a new task.
/edit/<task_id>/: Page to edit an existing task.
/delete/<task_id>/: Deletes a task.
/complete/<task_id>/: Marks a task as completed.
Testing

Run tests using Django's testing framework:

bash
Copy code
python manage.py test

**License**
This project is licensed under the MIT License.
