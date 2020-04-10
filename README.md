# Python Flask App!

A small web app for learning Python Flask and getting to know the Flask microFramework. In this application there are users who can post stuff and see other users post. users can also follow other users.

Link for the Flask Tutorial whihc I followed (https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world).
  
# Full Stack Application Development Using Python-Flask

## A Brief Introduction

A full stack application using python flask and and a suitable database with it. (SQLite).
Python-Flask is a micro web framework written in Python which is used to develop small and large scale web applications. It is easy to use and its also scalable.


# Pre-requisites

## Python and Python Flask

One must have Python installed in his local system for deploying this Full stack application easily. Other than Python also  install Python-Flask.


# Running this Web Application
01) Download the git repository
02) Open cmd or VS Code terminal.
03) Goto to the project's working directory
04) activate the virtual environment and set the FLASK_APP environment variable (setting up starting point of the application).

    ``` venv\Scripts\activate ```
    
    ``` set FLASK_APP=my_flask_app.py```
    ```
    flask run
    ```
# Checking the User Interface

https://localhost:5000/


# Few Aspects Related To Using Python-Flask

## Testing

Something that is not tested can be a headache. Python Flask actually provides a way to test your application, We can simply use libraries named as PyTest for testing Flask web services and APIs


## Documentation

This RESTFUL-API is written using Python-Flask, Huge, extensive and detailed documentation for flask is provided (http://flask.pocoo.org/docs/1.0/), Furthermore a very strong support is also there on multiple platform all around the web.

## Deployment

In the current scenario, Python-Flask own development web server is used to run the service. one must not use this technique on a production web server, Mulitple other web servers dedicated for running such type of service are present such as "Gunicorn" is a good example, we can also use "Apache" or "Nginx" for that. Also proper database either SQL or No-SQL depends on the usage setup must be used with the deployment.
