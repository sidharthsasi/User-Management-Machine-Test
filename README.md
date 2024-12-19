User Management System

This is a full-stack User Management System built using Django, Django REST Framework, and frontend technologies like HTML, CSS, and JavaScript. It provides user registration, login, profile management, and user listing functionalities.

Project Setup

1. Clone the Repository


git clone https://github.com/sidharthsasi/User-Management-Machine-Test.git


cd user_management


2. Create and Activate a Virtual Environment


python -m venv venv


venv\Scripts\activate



3. Install Dependencies


pip install -r requirements.txt



4. Set Up the Database


python manage.py migrate



5. Create a Superuser

python manage.py createsuperuser


6. Start the Development Server


python manage.py runserver


API Endpoints

1. POST /api/accounts/register/

2. POST /api/accounts/login/

3. GET /api/accounts/profile/

4. PUT /api/accounts/profile/

5. GET /api/accounts/users/

6. POST /api/accounts/logout/







