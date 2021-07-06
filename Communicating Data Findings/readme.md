# (Communicating Data Findings of Ford GoBike)
## by (Govardhan K)


## Dataset : Ford Go Bike Data

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco
Bay area. also, it represents trips taken by members of the Ford Go Bike service for month of February of 2019. Data consists of info about trips taken by service's members, their types, their age, their gender, duration of trips etc.

> There are 174,952 transactions in the dataset. 

a] There are two variables ['start_time, 'end_time'] are in datetime format which talk about journey start and end times
    
    i. From these variables, additional start and end variables such as year, month, date, weekday, hour are computed
    
b] Start and end location latitude and longitude are in float

c] user_type, member_gender, bike_share_for_all_trip are in category

The following variables are cleaned by data wrangling process to make data set clean for exploration

1. start_time & end_time to be converted to date time
2. start_station_id & end_station_id to be converted to object
3. user_type, member_gender, bike_share_for_all_trp to be converted to category
4. member_birth_year to be converted to int
 



## Summary of Findings

> The duration of trip time in mins has a long tail towards right side which is not giving any insights.  Hence, log transformation is applied to get insights

## Key Insights for Presentation

> Age: The distribution is right skewed with a peak between 25 to 35

> Duration: The distribution is right skewed with  a bump at the starting. We are not getting the right pitcure. Hence,  I applied   the log transformation on the x axis. The distribution looks normally distributed with a peak between 250-500
> 
> Start_time: The distribution is bi-modal with peaks at 9 and 6 PM. It is presumed that the users are mostly the employees.
> Duration: The distribution is right skewed with  a bump at the starting. We are not getting the right picture.
> There are no insights brought with multivariate analysis. We were able to ring as much relationships as we can in bivariate analysis
