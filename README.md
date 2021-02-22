# Django Rest Framework Boilerplate

With custom user model, tests and Travis CI deployment.

To spin up the server, run migrations and create super user
`docker-compose up`
`docker-compose run app sh -c "python manage.py createsuperuser`

To run tests
`docker-compose run app sh -c "python manage.py test && flake8`
