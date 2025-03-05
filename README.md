# Blog_post 
## Overview
This is a web application built with Django for user in order to manage their post. They can make a post ,add comments to others post ,edit also delete their post.

Users are required to authenticate using their email and password.users that are not authenticated can only view others post.

## Features
- **User Authentication:**
  - Users can register and access tasks after authentication using JWT (JSON Web Tokens).
  - Token-based authentication with `rest_framework_simplejwt`.
  
## Endpoints
### User Endpoints
- **POST** `/api/auth/register/` - Register a new user.
- **POST** `/api/token/` - Obtain a JWT token for authentication.
- **POST** `/login/` - Login registered users.
- **POST** `/logout/` - Users can logout.
- **POST** `/profile/` - Users can view their profile.
## Prerequisites
- Python 3.10 
- pip (Python package installer)
- VS Code
## Clone the Repository
git clone https://github.com/Bisruxa/blog_post.git
# Navigate to the project directory: 
cd blog_post
## create and activate a virtual environment
use "python -m venv venv" to create
use "source venv/Scripts/activate" to activate 
## install django and create django project 
pip install django 
django-admin startproject Task_managemnt . 
## run migrations
python manage.py makemigrations
python manage.py migarte
## run server
python manage.py runserver
