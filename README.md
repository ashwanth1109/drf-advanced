# drf-advanced

Commands run
```sh
docker-compose build

docker-compose run app sh -c "django-admin.py startproject app ."

docker-compose run app sh -c "python manage.py startapp core"

docker-compose run app sh -c "python manage.py test"

docker-compose run app sh -c "python manage.py makemigrations core"

docker-compose run app sh -c "python manage.py test && flake8"

docker-compose up

docker-compose run --rm app sh -c "python manage.py startapp user"
```

