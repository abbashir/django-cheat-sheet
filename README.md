# django-cheat-sheet

# Virtualenvwrapper-win
### using pip
<code>pip install virtualenvwrapper-win</code>

# Create Env
mkvirtualenv <name>

# Env List
Lsvirtualenv

# Remove 
rmvirtualenv <name>

# Activate
workon [<name>] or cmd /k  workon [<name>]

# Deactivate
Deactivate



Freeze Cheat Sheet
# Install 
Pip install freeze

# generate text file
pip freeze > requirements.txt

# install all the dependencies.
pip install -r requirements.txt



Django Cheat Sheet
# Install Django
pip install Django

# Create your project
django-admin startproject PROJECTNAME

# Run Server
python manage.py runserver

# Create an app
python manage.py startapp APPNAME

# Create migrations
python manage.py makemigrations

# Run migration
python manage.py migrate

# Collect Static Files
python manage.py collectstatic








