# Overview

Using a months worth of data from a public bikesharing service from New York, we are tasked with putting together a presentation to show potential investors in order to gain funding for a similar service in Des Moines, Iowa. With the wide variety of demographic data and key geographical and time metrics, we used Tableau to consolidate these visualizations into one easily accessible story board.

# Results

Below are the visualizations for the completed analysis. Use this [link](https://public.tableau.com/app/profile/tyler.sanzo/viz/CitiBikePresentationChallenge/NYCCitibikeStory?publish=yes ) to view the presentation on Tableau public.

## Number of trips by ride duration
![ride duration](https://github.com/tyler-sanzo/bikesharing/blob/main/images/ride_duration.PNG)

This graph shows that the majority of trips fall between 3 and 10 minutes. We see ride count drop off significantly at 10 minutes and a near negligible amount lasting longer than 50 minutes.

## Ride duration by gender

![ride duration gender](https://github.com/tyler-sanzo/bikesharing/blob/main/images/ride_duration_gender.PNG)

Similar results from the previous visualization as expected. Here it can be noted that Males make up the majority of ridership by a large margin.

## Peak Hours Heatmap

![Overall Peak Hours](https://github.com/tyler-sanzo/bikesharing/blob/main/images/peak_hours.PNG)

This heatmap is used to show the peak hours by day of the week. Note that weekdays find their surge hours during the start and end of the business day while weekends peaks are spread throughout mid day. During weekdays, majority of utilization is likely done by those commuting.

## Peak Hours Heatmap by Gender

![Overall Peak Hours Gender](https://github.com/tyler-sanzo/bikesharing/blob/main/images/peak_hours_gender.PNG)

This is the same heatmap filtered by gender. Similar surge hours are shared between all 3 but it can be noted again that Males make up the majority of ridership.

## Peak Hours Heatmap by Gender and User Type

![Peak Days by gender and usertype](https://github.com/tyler-sanzo/bikesharing/blob/main/images/peak_days_gender_usertype.PNG)

This heatmap is a more broad view showing the highest ridership by day of the week. We also used the usertype metric here which shows that ridership is made up mostly by those who are service subscribers. 


## Ride Duration by Age

![Ride duration by age](https://github.com/tyler-sanzo/bikesharing/blob/main/images/ride_duration_age.PNG)

This plot shows the average ride duration vs birth year. We can see that as age decreases, average checkout time increases. Note that in 1967 there seems to be a spike among older riders; this is a result of a low sample size being skewed by a single rider or handful of riders checking out a bike for an unusually long amount of time.


## Most Popular Pickup locations

![Map](https://github.com/tyler-sanzo/bikesharing/blob/main/images/map.PNG)

This map was created to show the spread of pickup locations throughout the city. We can see that the map is most populated in Manhattan which makes sense because it is the most densely packed borough in New York City.


# Summary

The results of this analysis show that the majority of ridership is made up of Males and ride duration is between 10 and 30 minutes. Additionally, the bulk of riders are contained in densely packed, centralized areas where foot traffic is heavy. Using this same dataset, another interesting correlation we might be interested in would be average trip duration vs start time(hour). We would be able to visualize at what time riders tend to take longer vs shorter trips. One other map that could be helpful to understand ride trends would be using both start and end locations to map out the most popular routes riders take. This could be used to know which stations need their bikes serviced and replenished more than others.