1. создать venv
'python3 -m venv venvname'

install requirements: 
`pip install -r requirements.txt`

применить миграции
'python manage.py migrate'

run project:
`python manage.py runserver`

run django-extensions console: 
`python manage.py shell_plus --ipython`