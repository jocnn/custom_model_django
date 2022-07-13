Custom Model and Custom User Authentication using Django
===
Abstract: Aplicación que muestra un modelo de datos personalizado, y un inicio de sesión y registro de usuario con campos personalizados
## Papar Information
- Title:  `Custom Model and Custom User Authentication`
- Authors:  `jocnn`

## Install & Dependence
- python 3.10.5
- vscode


## Use
- for run
  ```
  python manage.py runserver
  ```
- for test
  ```
  python manage.py test
  ```



## Directory Hierarchy
```
|—— .gitignore
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
|    |—— home.png
|    |—— login.png
|    |—— signup.png
|—— manage.py
|—— templates
|    |—— base.html
|    |—— home.html
|    |—— registration
|        |—— login.html
|        |—— signup.html
```

Home
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/home.png)

Login
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/login.png)

SignUp
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/signup.png)

Admin
===
![Image text](https://github.com/jocnn/custom_model_django/blob/main/img/admin_user.png)