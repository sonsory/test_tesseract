## web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker pythoncode:app

web: gunicorn pythoncode:app --bind 0.0.0.0:${PORT}
## web: gunicorn uvicorn.workers.UvicornWorker server:app
## web: gunicorn mysite.wsgi --log-file -
## web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker server:app
