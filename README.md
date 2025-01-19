# Authentication
Simple User Signup, Login, Logout, Password change, Forgot Password Authentication Fetures Showing Web Application.
## Requirements
Python 3.7+
Django 4.0+

## Installation
Clone the repository:

```bash
  git clone https://github.com/your-username/employee-management-api.git
  cd employee-management-api
```

Create a virtual environment:
```bash
  python3 -m venv venv
  source venv/bin/activate
```

Install dependencies:
```bash
  pip install -r requirements.txt
```

Apply migrations:
```bash
python manage.py migrate
```

Create a superuser (for accessing the Django Admin and generating JWT tokens):
```bash
python manage.py createsuperuser
```

Start the development server:
```bash
python manage.py runserver
```
