# taski-docker
docker compose up -d --build<br>
docker compose exec backend python manage.py migrate<br>
docker compose exec backend python manage.py collectstatic<br>
docker compose exec backend cp -r /app/collected_static/. /backend_static/static/<br>
