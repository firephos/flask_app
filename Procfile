release: ./release_tasks.sh
web: gunicorn flask_app.app:create_app() -b 0.0.0.0:$PORT -w 3
