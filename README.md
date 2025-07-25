Create venv environment

```
python -m venv tutorial-env
```

Activate venv environment

On Windows, run:
```
tutorial-env\Scripts\activate
```
On Unix or MacOS, run:
```
source tutorial-env/bin/activate
```

Install django in venv

```
py -m pip install Django
mkdir djangotutorial
```
Then, run the following command to bootstrap a new Django project:

```

...\> django-admin startproject mysite djangotutorial

The development server¶
Let’s verify your Django project works. Change into the djangotutorial directory, if you haven’t already, and run the following commands:

/ 
...\> py manage.py runserver

our apps can live anywhere in your Python path. In this tutorial, we’ll create our poll app inside the djangotutorial folder.

To create your app, make sure you’re in the same directory as manage.py and type this command:

/ 
$ python manage.py startapp polls

```

To play with django shell api

```
py manage.py shell
```

