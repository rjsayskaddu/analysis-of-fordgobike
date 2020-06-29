# fordgobike-system-data
Ford GoBike system Data Analysis and Exploration
This was one of the projects I worked at as part of Udacity Data Analyst Nanodegree Course. I have used Python visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships.

# Summary of Findings
In total there are 372 stations from where the users can rent a bike.

In this dataset there are 2 types of users (Subscriber and Customer). In most of the cases the user is Subscriber (approx 7 times more) and the rest of the users are Customer.

In the year 2018, the amount of customers and subscribers increases during the summer.

The Subscriber had a high demand at 8-9 am and then at 5-6 pm. In the case of the  Customer there is not big difference in the morning and afternoon, but it looks like there is more demand around 5pm.

I found that there are 3 stations in which the number of rides made by customers was higher compared to the subscribers.


I started my analysis by looking at the structure of the dataset.The main area of interest was what are the factors influencing the trip duration.

This dataset is from the Ford GoBike System data (a bike rental company), with 6930 bikes in this dataset with 3,254,325 rows and 13 features.

Data wrangling for this dataset consisted of converting the data files, combining months worth of datasets into 1 dataset and dropping several of the unnecessary rows that would not be used in the data analysis.

In the exploration, I found there was a trend between number of trips and average trip duration coming to just under 10 minutes, with some trips going up to 300 minutes and more! I found there was a surprisingly consistent minimum of bike trips throughout the years, always just below 200 minutes. JWe saw longer trips in April and August while May had fewer trips that lasted as long. When adding the subscription variable (user_type) we found subscribed users had shorted bike trips than normal users(customers) consistently. Normal users (Customers) bike times were consistently longer than subscribers throughout the year.
