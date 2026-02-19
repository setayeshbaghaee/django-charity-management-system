## Django Charity Management System
## Overview

A role-based Charity Management System built with Django.
This project simulates a real-world donation platform where users can explore charity causes and contribute through structured donation workflows.

The main focus of this project was designing relational models, implementing clean business logic, and structuring a scalable Django application following best practices.

## Key Features
### User Management

User registration and authentication

Profile management

Role-based permissions (Donor, Charity Organizer)

### Charity Causes

Browse available charity causes

Detailed cause pages (title, description, funding goal, images)

Organized cause management

### Donation System

Donate to specific causes

Donation records linked to donors and causes

Basic donation tracking logic

### Admin Dashboard

Full backend control using Django Admin

Manage users, charity causes, and donations

Easy operational data management

## Project Architecture

The project follows Django’s app-based architecture.
Each component is separated into its own application to ensure maintainability and scalability.
```bash

django-charity-management-system/
│
├── about_us/        # Informational pages
├── accounts/        # Authentication and user profiles
├── charities/       # Charity cause models and views
├── charity/         # Donation business logic
├── tests/           # Automated tests
├── db.sqlite3       # Development database
├── manage.py        # Django CLI entry point
├── requirements.txt # Python dependencies
└── README.md
```


This modular structure keeps responsibilities clearly separated and simplifies future expansion.

### Technologies Used

Python

Django

SQLite (development database)

HTML / CSS

Django Templates

Django ORM

Django Admin

## Getting Started

```bash

git clone https://github.com/setayeshbaghaee/django-charity-management-system.git
cd django-charity-management-system
python -m venv venv
On Windows:
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser (Optional)
python manage.py runserver

```

## What I Learned

Designing relational database models for real-world donation workflows

Implementing role-based access control

Managing backend operations through Django Admin

Structuring a modular Django application

Connecting templates with backend logic cleanly

Translating business requirements into maintainable code

## Future Improvements

Integrate a real payment gateway

Convert the project into a RESTful API using Django REST Framework

Implement JWT authentication

Add email notifications upon donation

Improve UI with responsive design

Deploy to a production environment

## Author
Setayesh Baghaee

Computer Engineering Student
