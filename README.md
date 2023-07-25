# Django-Setup

The Django Setup is an open-source repository where you can find the initial setup that you need to start your path through the most important Python framework for web development: Django :snake:

This repository contains the basic structure for any project build with Django, follow the next steps to clone this repo:

### 1. Clone this repository

The first thing you need to do is to open your terminal/cmd, access to the directory where you want to keep your project, then copy and paste this code:

##### HTTPS

```git clone https://github.com/jesusalberto18/Django-Setup.git```

#### SSH

```git clone git@github.com:jesusalberto18/Django-Setup.git```

And that's it! It creates a local copy of this repository in your machine.

```
NOTE: This project contains 2 important folders named 'Main' & 'App'. 'Main' contains the
main documents for this project, when you create a new project this folder inside it is named
after (in this case, it creates a Django-Setup folder inside the Django-Setup project), for
a better explanation it was renamed as 'Main', you could rename it anything you want and there
won't be an error.
```

Or you could start a project from scratch if you prefer...

### 2. Starting a Django project

To start a new project in Django, first you have to start a virtual environment by accessing to the directory where you'll be working and type:

```python3 -m venv {virtual_environment}```

Then activate your virtual environment by ```cd``` to it and type:

```source {virtual_environment}/bin/activate```

Once you've done it, you can initialize a new project by typing the next line in your terminal/cmd:

## Donate

<a href="https://www.paypal.com/paypalme/j2al444">
<img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" />
</a>

```django-admin startproject {project_name}```

Then ```cd``` to your new project and migrate the database to enable it for your project, you do so by typing:

```python3 manage.py migrate```

Next you need to create one or several apps to distribute the functions of your project, in the same folder type:

```django-admin startapp {app_name}```

The last step for creating the whole structure for your new project is running the server, for this you need to type:

```python3 manage.py runserver```

You should see your new project running at your ```localhost:8000```

or ```https://127.0.0.1:8000```

#### Congratulations! You have now created your first project on Django :snake:
