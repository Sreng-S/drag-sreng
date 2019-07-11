web: gunicorn dragsreng.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=dragsreng --loglevel=info
