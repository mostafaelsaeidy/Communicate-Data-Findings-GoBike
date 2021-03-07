# (GoBike System Data)
## by (Mostafa Mohamed Mostafa)


## Dataset

> GoBike Data is a dataset for bike trips .
  Dataset have 16 columns :

1 duration_sec

2 start_time

3 end_time

4 start_station_id

5 start_station_name

6 start_station_latitude

7 start_station_longitude

8 end_station_id

9 end_station_name

10 end_station_latitude

11 end_station_longitude

12 bike_id

13 user_type

14 member_birth_year

15 member_gender

16 bike_share_for_all_trip
 
we made some data wrangling:
 
convert start_time, end_time to Datetime.
 
convert user_type to category.
 
extract month, day and hour from the start_time and save them in separate 
columns.

## Summary of Findings

  the most common values almost in the range of 200:1K seconds.
  
  Subscriber type is the most common type
  
  all trips happened at February month.
  
  Wednesday , Friday almost equal . 
  
  Thursday have the most bikers.
  
  5 PM, 8 AM is the most hours have bikers.
  
  the average customer duration is higher than subscriber although the number of   subscriber is greater than number of customer 
  
  Saturday and Sunday have the most average duration.
  
  Thursday has the most bikers in customer and subscriber type
  
  5 PM, 4 PM has the most bikers in customer type.
  
  5 PM and 8 AM has the most bikers in subscriber type.
  
  11 PM the duration of biking is longer than any hour for customer type 
  
  2 AM, 3 AM the duration of biking is longer than any hour for subscriber type 


## Key Insights for Presentation

Tuesday, Thursday, Wedensday have the most bikers in the week (company should provide alot of bikes in these days).

8 AM and 5 PM is the most hours have bikers in the day (company should provide alot of bikes in these hours).