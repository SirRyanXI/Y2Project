# Run these start up commands in the terminal 
virtualenv env
env\scripts\activate
pip install django
python -m pip install --upgrade pip
pip install django-crispy-forms
python -m pip install Pillow
pip install stripe
python manage.py runserver
