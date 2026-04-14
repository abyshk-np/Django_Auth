Django Authentication System

A simple and secure Django project that demonstrates user authentication using Django's built-in authentication framework. This project includes user registration, login, logout, and access control.

Features

* User Registration
* User Login and Logout
* Password Security using Django Auth
* Django Admin Panel Integration

Tech/Tools

* **Backend:** Python, Django
* **Frontend:** HTML, CSS
* **Database:** SQLite
* **Authentication:** Django Built-in Authentication System

Simple Project Logic

* Users register using a sign-up form.
* Passwords and users are securely stored using Django’s authentication system.
* Registered users can log in.
* New users are redirected to the login page.
* Users can log out securely using Django’s logout mechanism.

Fields:

* `username`
* `email`
* `password`
* `is_authenticated`

No custom models are required, as Django's default authentication system handles user management efficiently.

Installation & Setup

```bash
git clone https://github.com/abyshk-np/Django_Auth.git
cd Django_Auth
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 🔑 Admin Access

```bash
python manage.py createsuperuser
```

Open: http://127.0.0.1:8000/admin/



Screenshots

![Path Page](https://github.com/abyshk-np/Django_Auth/blob/main/ACCOUNTS/IMAGE/PATHS.png)
![Login Page](https://github.com/abyshk-np/Django_Auth/blob/main/ACCOUNTS/IMAGE/LOGOUT_SIGNIN.png)
![Home Page](https://github.com/abyshk-np/Django_Auth/blob/main/ACCOUNTS/IMAGE/REGISTRATION.png)
