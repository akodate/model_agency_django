web: gunicorn config.wsgi:application
worker: celery worker --app=model_agency.taskapp --loglevel=info
