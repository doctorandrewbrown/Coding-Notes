## django file structure
- showing a project called charity_shop with one app called home. Note project, any apps and manage.py are at the same level as is templates folder for base templates. 
``` shell
gitpod /workspace/boutique-ado (main) $ tree -L 2
.
├── boutique_ado
│   ├── asgi.py
│   ├── __init__.py
│   ├── __pycache__
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── home
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   ├── models.py
│   ├── __pycache__
│   ├── templates
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── manage.py
├── media
│   └── homepage_background_cropped.jpg
├── README.md
├── reqirements.txt
├── static
│   └── css
└── templates
    ├── allauth
    └── base.html

11 directories, 18 files
```
