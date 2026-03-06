# Overview

A simple blog website built with Django where users can create, read, update, and delete blog posts.
This project is designed to demonstrate Django basics such as models, views, templates, authentication, and CRUD operations.

## Screenshots
<img width="1511" height="882" alt="login" src="https://github.com/user-attachments/assets/17be6622-d0b0-4ddb-9a9f-dd57e89af01d" />

<img width="1284" height="796" alt="registration" src="https://github.com/user-attachments/assets/85fc5f13-143a-4fff-8e49-c6cc300ff3fa" />

<img width="1184" height="797" alt="home" src="https://github.com/user-attachments/assets/ed964d6a-9ec6-430a-83fd-d3dcb8408c02" />

<img width="1216" height="719" alt="create post" src="https://github.com/user-attachments/assets/96f73fb5-a1e9-41c4-9f74-65e74d4033a7" />

<img width="1182" height="746" alt="admin" src="https://github.com/user-attachments/assets/d02039a5-2d7c-4fef-8a63-24a1184085ba" />

https://github.com/user-attachments/assets/dc214051-bf85-41be-b3d6-5e2d147626bb



## Features
	•	User registration & login
	•	Create, edit, and delete posts
	•	View all posts or individual posts
	•	Responsive design
	•	Admin dashboard for managing content

## Tech Stack
	•	Backend: Django (Python)
	•	Frontend: HTML, CSS, Bootstrap
	•	Database: SQLite (Development)
	•	Authentication: Django’s built-in authentication

## Installation & Setup
1.	Clone the repository
   ```
    git clone https://github.com/username/django-blog.git
    cd django-blog
  ```
2.	Create and activate a virtual environment
   ```
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
  ```
3.	Install dependencies
   ```
pip install -r requirements.txt
  ```
4.	Run database migrations
   ```
python manage.py migrate
  ```
5.	Create a superuser (admin)
   ```
python manage.py createsuperuser
  ```
6.	Run the development server
   ```
python manage.py runserver
  ```
## Future Improvements
	•	Add categories/tags
	•	Implement search functionality
	•	Allow image uploads for posts
	•	Add pagination

## License

This project is licensed under the MIT License.
