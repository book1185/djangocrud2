web: gunicorn crud.wsgi
release:python3 manage.py makemigrations --noinput
release:python3 manage.py collectstatic --noinput
release:python3 manage.py migrate --noinput