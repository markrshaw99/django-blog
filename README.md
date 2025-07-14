# Codestar Blog

A simple Django blog web app for Codestar challenge.

## Setup Instructions

1. Create and activate a Python 3.12+ virtual environment named `.venv`:
   ```bash
   python -m venv .venv
   source .venv/Scripts/activate  # On Windows
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run migrations:
   ```bash
   python manage.py migrate
   ```
4. Start the development server:
   ```bash
   python manage.py runserver
   ```
5. Visit [http://127.0.0.1:8000/blog](http://127.0.0.1:8000/blog) to see "Hello, blog!".

## Notes
- The `.venv/` folder is excluded from version control via `.gitignore`.
- The app uses Django 4.2.1 LTS.
