# Dependencies

Django 2.2.1, Python 3.5.5/3.7.2

# Local Development
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

- To change the port run `python manage.py runserver 8080`
- To create the db run `python manage.py migrate`
- To connect to the db run `sqlite3 db.sqlite3`

## Important

Don’t use this server in anything resembling a production environment. It’s intended only for use while developing. (We’re in the business of making Web frameworks, not Web servers.)

## Hot Reloading

The development server automatically reloads Python code for each request as needed. You don’t need to restart the server for code changes to take effect. However, some actions like adding files don’t trigger a restart, so you’ll have to restart the server in these cases.

