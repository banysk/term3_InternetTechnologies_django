web: gunicorn bossofthisgym.wsgi --log-file -
release: python manage.py migrate
heroku config:set DISABLE_COLLECTSTATIC=1