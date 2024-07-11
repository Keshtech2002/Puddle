# Puddle

### Virtual Enviroment
- Created a virtual environment on my local machine to host all dependencies
- Install dependencies ```pip install django```

### Django Project
1. Create project ```django-admin startproject puddle```
2. To run the project server ```python manage.py runserver``` inside the project ```puddle``` folder

### Django App
3. Created a new django app ```core``` using ```python manage.py startapp core```
4. Add the created app to settings.py of project ```puddle```
    ```
        INSTALLED_APPS = [
        "core",
    ]
    ```

### Tailwind CSS
- CDN added to head tag ```<script src="https://cdn.tailwindcss.com"></script>```

