release: python ToDo/manage.py makemigrations--no-input

release: python ToDo/manage.py migrate --no-input

web: gunicorn --pythonpath ToDo ToDo.wsgi --log-file