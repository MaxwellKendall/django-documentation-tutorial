# [Django Tutorial from Documentation](https://docs.djangoproject.com/en/2.2/intro/tutorial01/)

## Dependencies

Django 2.2.1, Python 3.5.5/3.7.2

## Local Development
Run `python manage.py runserver`

You'll see the following in the command line:

```
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are applied.
Run 'python manage.py migrate' to apply them.

May 15, 2019 - 15:50:53
Django version 2.2, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

- To change the port/base run `python manage.py runserver base:port`
- To create the db run `python manage.py migrate`
- To connect to the db run `sqlite3 db.sqlite3`
  - To show tables run .schema
