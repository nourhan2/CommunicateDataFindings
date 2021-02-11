# Ford GoBike System Data
## by Nourhan Mohamed Ahmed


## Dataset

> This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
It has 183412 row and 16 columns 
duration_sec                 int64 trip duration in second
start_time                  object trip start time
end_time                    object trip end time
start_station_id           float64 trip start station id
start_station_name          object trip start station name
start_station_latitude     float64 trip start station latitude
start_station_longitude    float64 trip start station longitude
end_station_id             float64 trip end station id
end_station_name            object trip end station name
end_station_latitude       float64 trip end station latitude
end_station_longitude      float64 trip end station longitude
bike_id                      int64 
user_type                   object user type (customer or subscriber)
member_birth_year          float64 
member_gender               object (male, female or other)
bike_share_for_all_trip     object (YES or NO)


## Summary of Findings

> The distribution of the trip duration is right-skewed, It has outliers and it requires a scale transformation.
The Age is right-skewed and most people are between 25 to 40, It has some problems with outliers.
The most trip day is wednesday and weekdays have trips more than weekends.
Most of the people are a subscriber and also males.
The most common hour that the trip start is about 8am or 5pm.
As expected trip duration is decreasing while the age is increasing.
Males are the most that but they all have a long trip duration.
Early trips have the longest trip duration and its decreasing over time.
Most of the subscriber are males, in contrast, most of the customers are others.
Thursday has the most trips for all genders.

## Key Insights for Presentation

> The featureas that affected the trip duration are: 
- Age that increasing while the trip duration is decreasing. 
- Gender dosen't affected too much but others make long trip duration in sunday.
- people make a long trip duration at early start hour.




