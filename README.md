# todo-list-app

A simple To-Do planner built with Django.

## Setup

To get this repository, run the following command inside your git-enabled terminal:

```bash
$ git clone https://github.com/arun6008/todo-list-app.git
```

You will need Django installed on your computer to run this app. Head over to [Django's official website](https://www.djangoproject.com/download/) for the installation guide.

Once you have installed Django, go to the cloned repo directory and run the following command:

```bash
$ python manage.py makemigrations
```

This will create all the migration files required to set up the database for this app.

Now, apply the migrations using:

```bash
$ python manage.py migrate
```

Next, create a superuser to manage the app:

```bash
$ python manage.py createsuperuser
```

Provide a **username, password, and email** for the admin user when prompted.

Now, let's start the Django server:

```bash
$ python manage.py runserver
```

Once the server is running, open [http://127.0.0.1:8000/todos](http://127.0.0.1:8000/todos) in your browser to use the To-Do Planner.
