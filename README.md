# ibotta_engineer_project

## Introduction
"""
### Data Engineer Take Home Project
=========

We’ve found that one of the best ways to evaluate engineering candidates is a take-home project. 
This project gives you a chance to work on some relevant code at home, and it gives us something concrete to 
discuss during your in-person interviews. Please choose the technologies that allow you to put your best foot forward. 
There are no bonus points given for finishing the project quickly.

### The Project

#### Preface
For test delivery, the data set here is relatively small (data from [Denver's open data catalog]
(https://www.denvergov.org/opendata)).  You should approach this test as though the data were 1000x the actual 
size and frequently updated by real-time events.


#### Task 1 
Download data about [Denver 311 service requests]
(https://s3.amazonaws.com/ibotta-data-engineer-test/311_service_requests.csv.zip) 
([original source](http://data.denvergov.org/download/gis/311_service_requests/csv/311_service_requests.csv)) 
and [traffic accidents](https://s3.amazonaws.com/ibotta-data-engineer-test/traffic_accidents.csv.zip) 
([original source](http://data.denvergov.org/download/gis/traffic_accidents/csv/traffic_accidents.csv)). 
This data set, which is *not* perfect, contains events in the City and County of Denver for the previous 12 months. 
Even as the data grows at a high rate, it should be reasonably queryable for the tasks below.

#### Task 2
Write a process to transform the data into a queryable data store. The city updates these files periodically, 
with a rolling 1-year window. The process should be flexible enough to be able to ingest new data when it is available. 
Queries against the data store should perform well even with rapid data growth.

#### Task 3
Explore the data to find interesting patterns or trends and then write queries for the resulting reports. 
The types of questions you might ask include the following:

- Are there seasonal trends to the different types of events?
- Which types of events are more common by geographic areas, as defined by coordinates or neighborhood?
- How long are typical response/resolution times? Do these differ by type of event, geography, or other factors?
- What correlations are there between the two data sets?

Treat your code as if it will be used in production to deliver insights to users. Think about readability 
and maintainability, and consider automated testing of code wherever possible.

### Deliverable
Please provide the code for the assignment either in a private repository (GitHub or Bitbucket) or as a zip file.


# Content
- Project Scope
- Prerequisites
  - Loading rameworks & libraries
  - Setting Spark Parallelism
- Extract Phase
- Transform Phase
- Analytics Phase
  - A. Easy querying techniques from temp SQL views
  - B. Are there seasonal trends to the different types of events?
  - C. Which types of events are more common by geographic areas, as defined by coordinates or neighborhood?
  - D. How long are typical response/resolution times? Do these differ by type of event, geography, or other factors?
  - E. What correlations are there between the two data sets?
- Machine Learning Prediction Model

# Technologies
- Python
- Databricks
- PySpark
- Keras
- Tensorflow

# Launch Date
- 10/3/2020

# Project status 
The project is ready for review.

# Sources
- An application of the RNN family
    Christophe Pere
    09/21/2020



