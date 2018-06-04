web: gunicorn config.wsgi:application
worker: celery worker --app=democookieproject.taskapp --loglevel=info
