# Django Snacks

PR Link: https://github.com/gracerosemary/django-snacks/pull/1

**Author**: Grace Choi
**Version**: 1.0.0 

## Overview
Create web site in Django with 2 pages
- home page
- about page
- create views/urls/templates as needed for home and about pages
- use ancestor template to contain navigation elements (base page)

## Getting Started
1. Create project
2. Initialize project
3. Install Django
4. Setup Server

## Helpful Commands
$ mkdir django_demo  
$ cd django_demo  
$ poetry init -n  
$ poetry add django  
$ tree  
$ poetry shell  
$ django-admin startproject django_demo  
$ python manage.py runserver  
$ python manage.py migrate  
$ python manage.py startapp demo  
$ python manage.py test  

## Architecture
Django, Poetry

## API
Create a project and add an app to the project. Add views, urlpatterns, templates so that the app can be routed to the server and displayed. Test using Django's built in testing tools.

## Change Log
02-27-2021 4:59pm - Completed lab and added basic styling to home page.