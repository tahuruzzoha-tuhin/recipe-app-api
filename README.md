# recipe-app-api

```
    docker-compose build
    docker-compose run app sh -c "python manage.py startapp app"
    docker-compose run app sh -c "python manage.py startapp core"
    docker-compose run app sh -c "python manage.py test"
    docker-compose run app sh -c "python manage.py makemigrations core"
    docker-compose run app sh -c "python manage.py createsuperuser"
    docker-compose run --rm app sh -c "python manage.py test && flake8"
    

```