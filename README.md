# recipe-app-api
Recipe App API



docker build .
docker-composer build

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."


docker-compose up

docker-compose run --rm app sh -c "python3 manage.py startapp core"



docker-compose run --rm app sh -c "python3 manage.py test"
docker-compose run --rm app sh -c "python3 manage.py createsuperuser"