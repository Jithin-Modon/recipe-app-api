# recipe-app-api
Recipe App API



docker build .
docker-composer build

docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app sh -c "django-admin startproject app ."


docker-compose up