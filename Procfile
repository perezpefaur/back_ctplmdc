release: python music_controller/main.py makemigrations --no-input
release: python music_controller/main.py migrate --no-input

web: gunicorn music_controller.wsgi