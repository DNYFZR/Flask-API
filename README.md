# API in a Flask

## Environmnet Set-up

In windows it you may get a permission error when setting up - run as admin will resolve this e.g. open VS Code as admin and use the terminal there.

To create the repo and set up the virtual environment.

In the terminal (admin) :
````py
# Make the directory and navigate to it
mkdir API-Flask && cd API-Flask

# Create virtual env
python -m venv flask_env

# Activate venv 
cd flask_env/scripts
activate.bat
cd ../../

# Update pip & install Flask
python -m pip install update pip 
pip install flask

# Make app dir
mkdir app
cd app
````

Now we have an active environment for developing our app.

---

## Python Modules

In the app folder in the repo, create the following files :

- \_\_init__.py : this can empty file lets Python know that we are working with modules.
- index.py : the base of the app