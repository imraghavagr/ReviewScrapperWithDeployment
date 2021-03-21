# ReviewScrapperWithDeployment

## Introduction

Review Scrapper is explicitly coded to scrap product reviews from www.flipkart.com
I have created it as a first step to learn databases, web API and deployment.

## Table of contents
* [Technologies](#technologies)
* [IntallationOfLibraries](#installation-of-libraries)
* [DeploymentSteps](#deployment-steps)

## Technologies
Project is created with:
* Python 3.6.9
* beautiful soup == 4.9.1, for parsing request data into html format
* Flask == 1.1.2
* pymongo == 3.11.3

For now database connection with pymongo is only made in the local web API which recides in flask_app.py
For deployment i have made a seperate file - 'app.py', which does not deals with database.

## Intallation Of Libraries
```
$ pip install -r requirements.txt
```
## Deployment Steps

Make sure to have app.py, requirements.txt, Procfile, Static and templates folder in the project directory. Open git bash and make your project directory as working directory. Also make sure to install heroku cli in your system.

```
$ Heroky login
$ git init
$ git add .
$ git commit -m "initial commit"
$ heroku create
$ git remote -v
$ git push heroku master
```

