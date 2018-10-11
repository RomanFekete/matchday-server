# matchday-server

## Requirements

* virtualenv

* python3


## Usage

cd into project root directory

### Preparation to using virtualenv
Make sure that you have python3 installed. 

Create separated environment
```
$ virtualenv -p python3 venv
```
Activate separated envirionment
```
$ source venv/bin/activate
```
Deactivate separated environment(while virtualenv is activated)
```
$ deactivate
```
### Install required packages
while virtualenv is active
```
$ pip3 install django
$ pip3 install djangorestframework
$ pip3 install django-heroku
$ pip3 install coreapi
```
### Run Aplication
```
$ python3 manage.py makemigrations
$ python3 manage.py migrate
$ python3 manage.py runserver
```
