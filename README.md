# BikeSharing - Tableau Data Visualization
## Analysis Overview
### Purpose
To analyze the bike trips dataset of New York Citi Bike and create data visualizations via Tableau Public in order to uncover the bike sharing trends and insights, such as user types and rental trends, for the month of August 2019. This analysis will be used as a business model for the in-planning bike-sharing business in Des Moines.


### Resources
+ **Software:** Tableau Public, Jupyter Notebook
+ **Datasource:** NYC Citi Bike's trip history data of August 2019, downloaded from [CitiBikeSystemData](https://ride.citibikenyc.com/system-data)
<br />(Converted the trip duration's data type to date time using Jupyter Notebook)

### Analysis Results
#### Project Visualizations
+ **Link to the analysis on Tableau Public:** [NYC CitiBike Aug-2019-Trips Analysis](link)
+ **Code for tripduration datatype convertion:** [NYC_Citibike_Challenge.ipynb](https://github.com/asama-w/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb)

This project analyzes the NYC Citi Bike trip history dataset of the month of August 2019.
The visualizations will be able to determine the distribution of users and the bike rental trends and answer three main questions:
+ Who use the Citi Bike services? To determine target group of customers.
+ When do they use the bike and for how long? To determine how many bike would be sufficient.
+ Where is the high-traffic of the bike rides? To determine the top locations of bike stations.

#### 1. Users Breakdown 

<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Users_breakdown.png width="70%" height="70%">

There are over 2.3 millions of bike trips in August 2019.
Approximately 65% of the users gender are male. For the user type, majority of the Citi Bikers are subscribers, contributing up to 81% of the total users, which implies that high number of users might be the NYC residents, or uses the bike regularly, or that the Citi Bike has a better subscription plan than the single trip deal.

#### 2. Top starting and ending location
The following visualizations show the top bike pick-up and drop-off locations, respectively. The circle-size and colour-intensity determine the density of the trips. The darker the colour and the larger the circle mean that there are more trips starting and ending there. 

The top locations of the bike rental are noticeably in the Manhattan, which may due to the high number of tourists present, highly populated residential and workplace downtown area, and major tourist attractions.

<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Top_starting_location.png width="70%" height="70%">
<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Top_ending_location.png width="70%" height="70%">

#### 3. Checkout time for all users and by gender
These visualizations show the length of the bike checkout time. The first visualization represents the trip duration of all users, the second visualization also shows the trip duration with the breakdown of the user genders. 

Majority of the users used the bike for less than 1 hour, specifically, most users rent the bike for less than 30 minutes. The trip duration peaks at around 5-6 minutes.

With the breakdown of genders, the graphs still follows the same trend of that of all users, with the male gender dominates the bike utilizations and tends to rent the bike for a longer time than other genders.

<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Checkout_time_users.png width="70%" height="70%">
<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Checkout_time_by_Gender.png width="70%" height="70%">

#### 4. Trips per hour and by gender
The following heatmaps show the number of bike trips per hours for all users and gender, respectively. The bike trips are significantly high during the rush hours on weekdays (from 7-9am in the morning and 4-7pm in the evening), which is possibly due to the commute from and to workplaces. However, the trip number are comparably lower for Wednesday evening, for which the reasons needed to be further analyzed, might due to the road closure, or bike station closure.
For the weekend, in contrast to weekdays, the trips are densely packed during the day, from 9am -6pm, although the number are not as high as weekday's rush hours. 

For the gender breakdown of the number of trips, the heat map patterns of male's and female's bike trips follow the trend of the all user's trips, with the majority trips are male-dominant bikers. The unknown gender uses the bike slightly more on the weekend, which might result from the occasionally users who want to relax and use the bike for the weekend outdoor activities.

<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Trips_per_hour.png width="70%" height="70%">
<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Trips_by_gender.png width="90%" height="90%">

#### 5. Trips per weekday 
To map out the number of users by the user type for each day of the week, the following visualization shows that the majority user type is subscriber, and most of them are male, correlating with the other visualizations that shows the male and subscriber-dominant users. The bikes are most utilized during the weekdays, with the peak on Thursday. 

On the contrary, the customers who is a non-subscriber use the bike more on the weekend, especially for the unknown gender customer. One possible reason for the higher number of unknown gender customer users may due to the unwillingness to provide specific information about themselves for the occasional bike rental.

<img src= https://github.com/asama-w/bikesharing/blob/main/Additional_images/Trips_weekday_users.png width="70%" height="70%">


### Analysis Summary
#### NYC Citi Bike Trip Data Summary
There are 2,344,224 users of the NYC Citi Bike in the month of August 2019, of which 81% of them hold the subscription, and the male gender dominates the number of Citi Bikers.


#### Two additional visualizations 
