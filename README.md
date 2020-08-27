# recipe-app-api
Recipe app source code

###Build docker
`docker build .`

###Build docker-compose
`docker-compose build`

###Start django project
`docker-compose run app sh -c "django-admin.py startproject app ."`

###Run tests
`docker-compose run app sh -c "python manage.py test"`

###Make migrations
`docker-compose run app sh -c "python manage.py makemigrations core"`

Add the app name at the command ends, if you get some errors.

