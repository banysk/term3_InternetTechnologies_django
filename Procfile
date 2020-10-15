web: gunicorn bossofthisgym.wsgi --log-file -
heroku config:set DISABLE_COLLECTSTATIC=1
release: python manage.py migrate