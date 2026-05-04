web: python manage.py migrate --noinput && gunicorn -k eventlet -w 1 mole_backend.wsgi --bind 0.0.0.0:$PORT --log-file -
