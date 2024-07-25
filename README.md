# Django-Poll-App
A Django backend website that enables the creation, editing and viewing of polls.

# Django Polls App

This is a simple polling application built with Django, following the official Django tutorial. The application allows users to create polls, vote on them, and view the results.

## Features

- Create polls with questions and multiple-choice answers.
- Vote on polls.
- View poll results.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Python 3.x
- Django
- PostgreSQL (if you are using PostgreSQL as your database)

## Getting Started

Follow these steps to get a copy of the project up and running on your local machine for development and testing purposes.

### Clone the Repository


`git clone https://github.com/yourusername/django-polls.git`

`cd django-polls`

### Create and Activate a Virtual Environment

It is recommended to use a virtual environment to manage dependencies.


python3 -m venv venv
`source venv/bin/activate` 
On Windows use `venv\Scripts\activate`
### Install Dependencies
Install the required Python packages.


`pip install -r requirements.txt`
### Apply Migrations
Apply the database migrations to create the necessary tables.

`python manage.py migrate`
### Create a Superuser
Create a superuser to access the Django admin interface.


`python manage.py createsuperuser`
Follow the prompts to set up the superuser account.

### Run the Development Server
Start the development server.


`python manage.py runserver`
Visit `http://127.0.0.1:8000` in your browser to see the application in action.

### Using the Application

Admin Interface:
Visit `http://127.0.0.1:8000/admin` to create polls and manage the application.

Polls Interface:
Visit `http://127.0.0.1:8000/polls` to view and vote on polls.
### Contributing
If you want to contribute to this project, please fork the repository and submit a pull request. We appreciate your help!

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

