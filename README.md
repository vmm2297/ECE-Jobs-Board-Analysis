# ECE-Jobs-Board-Analysis

Scrape jobs found at http://ece.ucsd.edu/jobs and find patterns
Helpful tutorial at http://newcoder.io/scrape/

## Features

 - Organize all job posting into a CSV file
 - Find common connection between postings (skills, languages, etc)
 - Classify types of jobs and experience needed
 - Relate it back to ECE classes

## Stack

### Python (Version 2):
 - [Scrapy](https://scrapy.org/): web scraping framework
 - [SQLAlchemy](https://www.sqlalchemy.org/): interact with databases (Postgres, MySQL, MS SQL, etc) without needing to write raw SQL code
 - [Pandas](https://pandas.pydata.org/): high-performance, easy-to-use data structures and data analysis tools ("Excel" but in Python)
 - [Numpy](http://www.numpy.org/): fundamental package for scientific computing ("MATLAB" but in python)
 - [Jupyter/IPython](https://ipython.org/): interactive computing, useful for data visualization
### Database:
 - [Postgres](http://www.craigkerstiens.com/2012/04/30/why-postgres/): popular database to store data
### Task Manager:
 - [Cronjobs](https://en.wikipedia.org/wiki/Cron#Predefined_scheduling_definitions): job scheduler for Unix-like computers
