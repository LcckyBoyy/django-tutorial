# Django Polls Tutorial Project

A simple Django polls application following the official Django tutorial.

## Setup

1. Create a virtual environment:
```bash
python -m venv myvenv
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
python manage.py migrate
```

5. Create a superuser (optional):
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

## Dependencies

- Django 5.2
- Django Debug Toolbar 5.1.0

## Project Structure

- `polls/` - The polls application
- `mysite/` - Project configuration
- `templates/` - Project-wide templates