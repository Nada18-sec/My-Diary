# My-Diary
This is a diary project created using Django and Python

Type the following commands into a terminal to create and activate a virtual environment and install the requirements:

$ python -m venv venv
$ source venv/bin/activate
$ python -m pip install -r requirements.txt

Then run the database migrations and create a superuser:

$ python manage.py migrate
$ python manage.py createsuperuser

Finally, run the local Django development server:

$ python manage.py runserver

