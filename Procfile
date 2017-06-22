web: gunicorn config.wsgi:application
worker: celery worker --app=stayfyt.taskapp --loglevel=info
