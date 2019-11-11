# Utilities Package
 A package of API and database monitoring utilities that I made with Flask during my internship at AgileField the summer of 2018. There are 2 different utilities bundled into this package. The utilities were requested as a bundle to automate the repetitive tasks of checking on APIs and sending SQL queries to an email blacklist database.
 1. Status: This utility shows a seried of panels with the names of various APIs and a green or red color with text to indicate whether the API was
  online or had crashed. 
 2. Blacklist: This utility allows users to search, delete, and add items to an email blacklist.

## Dependencies

This project was built with Flask on python 3. The frontend uses bootstrap and the backend connects to a PostgreSQL database. The following python packages are used:

* flask
* flask-wtf
* flask-bootstrap
* pg8000
* requests

## Usage

The project could be hosted locally by navigating to the root folder then using the standard method for starting Flask apps:
`FLASK_APP=utilities.py`
then 
`flask run.`

The project no longer functions as intended since the referenced APIs are no longer in use.
