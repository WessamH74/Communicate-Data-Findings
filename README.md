# Communicate-Data-Findings

## Dataset

I have used 2017-fordgobike-trip dataset for doing this project you can find it here https://s3.amazonaws.com/fordgobike-data/index.html
dataset has 519700 rows and 13 columns about station names, bike id, lcoation, time, duration and customer type
i have cleaned it and created new columns which would help me in analysis like day, month, duration in mintues and hour, and dropped others which would not help or i never use it
like duration in second or location


## Summary of Findings

in exploratory data analysis, I have done a lot of visualizations to reach my results such as the most duration of trips is 10 min
, most popular 10 start and end stations and I have found that San Francisco Ferry Building (Harry Bridges Plaza) and The Embarcadero at Sansome St are the most common start station
, while San Francisco Caltrain (Townsend St at 4th St) and San Francisco Ferry Building (Harry Bridges Plaza) are the most common end station, bikes with id 68 and 2178 are most used by users in this dataset
, 21.3% of the riders are Customers while 78.7% are Subscribers, Riders preferred riding bikes at Tuesday and Wednesday than Sunday, They do few trips in June, and most of their trips are in September, October, November
, the average time which Customers take in their trips is higher than the average of Subscribers, from 12 am to 6 am there is the least time, and It's obvious because they are sleeping
, the most frequency of Subscribers is 8-9 AM and 5-6 PM, the two intervals almost equal, i think because these are working hours, while Customers prefer doing trips from 8 AM to 6 PM
, the frequency of the Customer type on weekdays is almost equal, but they prefer doing trips on weekends, the frequency of the Subscriber type on weekdays is almost equal too and their trips almost in weekdays
, and there is no preferred day in each month, each month has a common different day, Customers prefer weekends afternoon hours, while Subscribers prefer weekdays specialy 8 AM and 5 PM


## Key Insights for Presentation

For the presentation, I'm trying to illustrate What is the duration of most rides? most popular start and end stations, the most common user type in the dataset
, then the most popular day and month.

after all of these single relationships, I'm showing some relationships between two variables by showing the relation between user type and the hours they ride bikes
, then the number of each type per day, and finally the number of trips for each day in each month 

In the end, I am going to finish the presentation by showing a multi relationship, What are the most common hours for each user in each day?
