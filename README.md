# Django Polls Tutorial Project

A simple Django polls application following the official Django tutorial.

## Setup

1. Create a virtual environment:
```bash
py -m venv myvenv
```

2. Activate the virtual environment:
```bash
myvenv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
py manage.py migrate
```

5. Create a superuser (optional):
```bash
py manage.py createsuperuser
```
Username : admin
Email : (can be left blank)
Password : (enter your password - characters won't be visible)
Password (again) : # re-enter


6. Run the development server:
```bash
py manage.py runserver
```

## Dependencies

- Django 5.2
- Django Debug Toolbar 5.1.0

## Project Structure

- `polls/` - The polls application
- `mysite/` - Project configuration
- `templates/` - Project-wide templates