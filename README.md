### steps for setup django project 

1. setup evrironment variable and activate

```

    python -m venv venv 
    venv/scripts/activate

```

2. install Django 

```

    pip install django

 ```

 3. create django project
 
 ```

    django-admin startproject lms
 
 ```
 
 4. create django app

 ```

    cd lms
    python manage.py startapp lmsapp

 ```

 5. django app integrate with project in setting.py file

 ```
 
    INSTALLED_APPS = [
    'lmsapp',
]

``` 

6. run server

```

    python manage.py runserver

```
