# Ford GoBike Trip Dataset
## by Zaid Baig A


## Dataset

> Data consists of info about trips taken by service's members, their types, their age, their gender, stations of starting and ending trips, duration of trips etc. 

### What is the structure of your dataset?
> The Dataset consists of a total of 183,412 records and 16 attributes

### What is/are the main feature(s) of interest in your dataset?
> The main features in the dataset according to the initial analysis are: duration_sec, start_station_id, end_station_id, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip

### What features in the dataset do you think will help support your investigation into your feature(s) of interest?
> The features that will help support the investigation are: duration_sec, start_station_id, end_station_id, user_type, member_birth_year, member_gender


## Summary of Findings

>The main finding we found during the data exploration phase are as follow:
1. The average time spent on the bike according to the sample set a little below a thousand seconds which in terms of minutes is approx 15mins
2. In our gender comaprison we find that the majority of the users are actually male with more than 70%. With women only having a little over 20% of the distribution
3. Majority of the users have birth years between between 1980s and 2000s, i.e, their approx age range is 20 to 40
4. the most popular station where users have as the starting point for the bike rental is "Market Street at 10th street" and the favourite end station to conclude their usage is "San Francisco Caltrain Station 2"
5. The number of users in weekends are way lesser than the number of users during the weekdays
6. Most non-subcriber type customer make use of rental bikes on more than the subcribers in terms of rent duration
7. Subscribers rent duration is constantly at 10 mins during Monday to Friday and about 12 mins during the weekends. This looks like subscribers have a fixed schedule and have incorporated the use rental bikes in their day to day activities.

## Key Insights for Presentation

> Datatype for timestamp attributes
1. The data present for date timestamp values are in object format. This is converted into date timestamp format
> Feature Engineering
1. The timestamp values are then used to generate the weekday values from them. Which is later used in the analysis of weekday vs weekend Rent usage in the analysis
2. The rent duration which are in seconds are re-generated into hours and minutes to fully understand and make it clear for the actual duration of the rent