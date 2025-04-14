To run:
Create virtual environment in root directory:
python -m venv venv
Activate venv in root directory:
venv\scripts\activate

then:
cd backend
python manage.py runserver

Note: For some reason, can't migrate since django create unnecessary session tables in db.

