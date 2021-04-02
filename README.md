# Django Rest Framework Boilerplate

With custom user model, tests and Travis CI deployment.

To build image, run migrations and create super user

`docker-compose run app sh -c "python manage.py wait_for_db && python manage.py migrate && python manage.py createsuperuser"`

To run tests

`docker-compose run app sh -c "python manage.py wait_for_db && python manage.py migrate && python manage.py test && flake8"`

To spin up server

`docker-compose up`
