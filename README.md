# ReviewScrapperWithDeployment

## Introduction

Review Scrapper is explicitly coded to scrap product reviews from www.flipkart.com
I have created it as a first step to learn databases, web API and deployment.


## Technologies
- Python 3.6.9
- beautiful soup == 4.9.1, for parsing request data into html format
- Flask == 1.1.2
- pymongo == 3.11.3

For now database connection with pymongo is only made in the local web API which recides in flask_app.py
For deployment i have made a seperate file - 'app.py', which does not deals with database.


