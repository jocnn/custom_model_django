Newspaper
===
Abstract: Aplicación de noticias que muestra un CRUD para agregar artículos, usuarios, seguridad al crear, editar y eliminar artículos con los dueños de los artículos, se agrego comentarios para los artículos. Se realizo el deployment en Heroku usando la db Postgres.
## Papar Information
- Title:  `Newspaper`
- Authors:  `jocnn`
## Install & Dependence
- asgiref==3.5.2
- crispy-bootstrap5==0.6
- dj-database-url==0.5.0
- dj-email-url==1.0.5
- Django==4.0.6
- django-cache-url==3.4.2
- django-crispy-forms==1.13.0
- environs==9.3.5
- gunicorn==20.1.0
- marshmallow==3.17
- packaging==21.3
- psycopg2==2.9.3
- psycopg2-pool==1.1
- pyparsing==3.0.9
- python-dotenv==0.19.2
- sqlparse==0.4.2
- whitenoise==5.3.0

## Use
- for run
  ```
  python manage.py runserver
  ```
- for test
  ```
  python manage.py test
  ```
- Deployment
  ```
  https://xax-news.herokuapp.com/
  https://xax-news.herokuapp.com/articles
  ```

## Directory Hierarchy
```
|—— .env
|—— .gitignore
|—— .venv
|    |—— bin
|        |—— Activate.ps1
|        |—— activate
|        |—— activate.csh
|        |—— activate.fish
|        |—— django-admin
|        |—— dotenv
|        |—— gunicorn
|        |—— pip
|        |—— pip3
|        |—— pip3.10
|        |—— sqlformat
|—— Procfile
|—— __README.md
|—— accounts
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— forms.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— tests.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— forms.py
|    |—— migrations
|        |—— 0001_initial.py
|        |—— __init__.py
|        |—— __pycache__
|            |—— 0001_initial.cpython-310.pyc
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— articles
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— forms.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— forms.py
|    |—— migrations
|        |—— 0001_initial.py
|        |—— 0002_comment.py
|        |—— __init__.py
|        |—— __pycache__
|            |—— 0001_initial.cpython-310.pyc
|            |—— 0002_comment.cpython-310.pyc
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— db.sqlite3
|—— django_project
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— settings.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— wsgi.cpython-310.pyc
|    |—— asgi.py
|    |—— settings.py
|    |—— urls.py
|    |—— wsgi.py
|—— img
|    |—— admin_user.png
|    |—— article_create.png
|    |—— article_delete.png
|    |—— article_detail.png
|    |—— article_edit.png
|    |—— articles_list.png
|    |—— home.png
|    |—— home_2_bootstrap.png
|    |—— login.png
|    |—— login_2_bootstrap.png
|    |—— password_change_done.png
|    |—— password_change_form.png
|    |—— password_reset_complete.png
|    |—— password_reset_form.png
|    |—— signup.png
|    |—— signup_2_bootstrap.png
|—— manage.py
|—— pages
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— tests.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— migrations
|        |—— __init__.py
|        |—— __pycache__
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— requirements.txt
|—— runtime.txt
|—— static
|    |—— css
|        |—— base.css
|    |—— js
|        |—— base.js
|—— staticfiles
|—— templates
|    |—— article_delete.html
|    |—— article_detail.html
|    |—— article_edit.html
|    |—— article_list.html
|    |—— article_new.html
|    |—— base.html
|    |—— home.html
|    |—— registration
|        |—— login.html
|        |—— password_change_done.html
|        |—— password_change_form.html
|        |—— password_reset_complete.html
|        |—— password_reset_confirm.html
|        |—— password_reset_done.html
|        |—— password_reset_form.html
|        |—— signup.html
```
Home
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/home_2_bootstrap.png)

Login
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/login_2_bootstrap.png)

SignUp
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/signup_2_bootstrap.png)

Admin
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/admin_user.png)
