web: gunicorn firstapp.wsgi --chdir backend --limit-request-line 8188 --log-file -
worker: celery worker --workdir backend --app=firstapp -B --loglevel=info
