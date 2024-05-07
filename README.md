# Personal-diary-using-Python-and-Django
This repository contains the project to build personal diary using python and Django . We have used Django admin site's advantage to authenticate the personal diary .
**Note:** The project is built with `Python 3.12.2`, but should work with any Python3 version .

## How To Run 

Type the following commands into a terminal to create and activate a virtual environment and install the requirements:

```sh
$ py -m venv venv
$ .venv\Scripts\activate
$ py -m pip install -r requirements.txt
```

Then run the database migrations and create a superuser:

```sh
$ py manage.py migrate
$ py manage.py createsuperuser
```

Finally, run the local Django development server:

```sh
$ py manage.py runserver
```
