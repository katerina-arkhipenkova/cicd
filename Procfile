web: gunicorn stocks_products.wsgi
release: python manage.py migrate
heroku config:set DISABLE_COLLECTSTATIC=1