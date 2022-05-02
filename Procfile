release: python main.py makemigrations --no-input
release: python main.py migrate --no-input

web: gunicorn music_controller.wsgi