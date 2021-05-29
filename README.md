
# setup-a-django-project
This repo is only for person that new in django web framework. In this repo i wrote a lot command for can setup a django project easily. I assume that you intalled Python. Let's get started!

## Select a name for your project folder.
`mkdir django_project && cd django_project`


## Create an environment to keep your coding environment tidy on your computer. I choose 'env' as a name.
`python -m virtualenv env`


## Activate this environment.
`env\Scripts\activate.bat`

or Linux & OS X
`source env/bin/activate`


## After the env activated you will see it in front of the line like;
(env) C:\Users\User\Desktop\django_project>


## Install Django
`pip install Django`
D is caiptal so we will install latest version of Django.
You can specify a version like that;
`pip install Django==3.2.2`


## Start Project
`django-admin startproject django_project .`
This dot is important to keep the files in the same directory.


## Run the server
Afer we installed Django, we are going to use `py manage.py ..` more than `django-admin`.

`python manage.py runserver`

You can specify a server port if it needs;
`python manage.py runserver 8045`


# If you came this far Congratulations! You have an emty django project! Let's improve this project a litle to write 'Hello World' on home page with an html file.

## Create an app. I put the app name is 'core'

`python manage.py startapp core`

## Modify settings.py 
Coming soon ⚓




