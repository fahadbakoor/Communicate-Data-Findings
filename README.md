# February 2019 FordGoBike Data Exploration and Visualization
### By Fahad Bakoor

## Dataset
the data set I am using today is for February 2019, which covers info about trips taken by service members, their types, age, gender, stations of starting and ending trips, duration of trips, etc.
#### columns:
- Trip Duration (seconds).
- Start Time and Date.
- End Time and Date
- Start Station ID.
- Start Station Name.
- Start Station Latitude.
- Start Station Longitude.
- End Station ID.
- End Station Name.
- End Station Latitude.
- End Station Longitude.
- Bike ID.
- User Type (Subscriber or Customer).
- Member Birth Year        
- Member Gender             
- Bike Share For All Trip

### Data wrangling process:
- change columns to correct data types 
- create a column for member's age 
- drop outlier in the age column 
- extract the day of week and hour from start_time and convert it to ordinal
- convert duration from seconds to minutes
- drop nulls

## Summary Findings
- More male riders than females 
- Thursday has the most number of trips
- most trips are short, around 17 min 
- ages are primarily between 20 and 40.
- Customers tend to take longer trips on average than Subscribers 
- duration of trips get shorter the older the rider
- There are more male riders than female 
- Men tend to take longer trips on average than women 
- customers trips are much longer on average compared to Subscribers,
- males trips are longer on average compared to female trips 
- rides on Sunday and Saturday on average, have the longest trip duration 
- rides at 2 AM and 3 AM on average have the longest trip duration


## Key Insights for Presentation
- Most of the trips are below 15 min
- riders on Sunday and Saturday, on average, have the longest trip duration
- riders on 2 AM and 3 AM on average have the longest trip duration
- Younger riders (18 to 50) tend to have longer trips
- trip duration starts to drop after the age of 50

