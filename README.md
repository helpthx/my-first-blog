
# Djando + sqlite3 + BootStrap + pythonanywhere

<p align="center">
 
<a href="" alt="">
        <img src="https://img.shields.io/eclipse-marketplace/last-update/notepad4e.svg" /></a>
        
<a href="" alt="">
        <img src="https://img.shields.io/dub/l/vibe-d.svg" /></a>
        
<a href="" alt="">
        <img src="https://img.shields.io/badge/Version-v1-green.svg" /></a>
        
<a href="" alt="">
       <img src="https://img.shields.io/pypi/pyversions/Django.svg" /></a>

  
<a href="" alt="">
       <img src="https://img.shields.io/github/repo-size/badges/shields.svg" /></a>

</p>
<p align="justify">
Simple project integrating django with bootstrap and sqlite3 database online on pythonanywhere focus in create a blog respositive with forms and views. There are a form which save user inputs in database. This simple project is a base for outhers projects based on a DjangoGirls tuto</p>


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
Python 3.6.7 
django 2, 1, 2, 'final', 0
bootstrap v4.1.3
pip 9.0.1
```

### Installing

* Install django last stable version
* Set the rigth password and ports on settings.py
* On manage.py ru

```
$ python3 manage.py makemigration
$ python3 manage.py migrate
```


## Running the tests

* Run
```
$ python3 manage.py migrate && python3 manage.py makemigration
```
* Make sure that there are tables from django admin and aplications.
* On /myapp dir run 
```
$ python3 manage.py runserver
```
* Acess the web aplication through:
```
http://127.0.0.1:8000/home/
```

## Online in pythonanywhere

[My Django Fist blog with pythonanywhere](http://helpthx.pythonanywhere.com/)



## Built With

* [Bootstrap](https://getbootstrap.com/) - Bootstrap used
* [Python3](https://www.python.org/download/releases/3.0/) - Main language
* [Django](https://www.djangoproject.com/) - Django API 
* [SQLite3](https://www.sqlite.org/index.html) - SQLite3 database
* [PythonAnyWhere](https://www.pythonanywhere.com) - Online Host


## Authors

* **João Vitor Rodrigues Baptista** - *Initial work* - [helpthx](https://github.com/helpthx)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Based on a tutorial project: [Tutorial Django Girls](https://tutorial.djangogirls.org/pt/)

## What's next ??
* [Django Oficial](https://docs.djangoproject.com/en/2.0/intro/tutorial01/)
* [New Coder](http://newcoder.io/tutorials/)
* [django-carrots](https://github.com/ggcarrots/django-carrots)
* [Starting with Django](http://www.gettingstartedwithdjango.com/)
