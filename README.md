# (Dataset Exploration Title)
## by Tina RAZAFINDRAKOTO


## Dataset

The dataset that will be processed in this project concerns data from the FordGobike system. This dataset includes information about individual trips taken in a bike share system covering the greater San Francisco Bay Area.

this set of data includes 16 columns and 183412 rows that containt float, integer and object values 
The colomns are composed by:
- duration_sec : The duration of use, expressed in seconds.
- start_time, end_time: The start and end time of the trip, expressed in date and time.
- start_station_id, end_station_id: The identification number of the start and end stations of the trip.
- start_station_name, end_station_name: The name of the start and end stations of the trip.
- start_station_latitude, start_station_longitude, end_station_latitude: The geographic coordinates of the start and end stations.
- bike_id: The identification number of the bike.
- user_type: The type of customer using the bike: subscribers or simple customer.
- member_birth_year : The year of birth of the customer.
- member_gender: The gender of the customer.
- bike_share_for_all_trip : Bike shared during the whole trip : yes or no.
- member_age: age of the member
- duration_min : duration of use in minutes

## Summary of Findings
- there is approximatively a maximum of 40000 user for age average of 34 years old
- the majority of trips are around 1 to 30 minutes with a peak around 10 minutes
- 90.5% of the people who use biike share are subscriber, 9.5% only are customer
- 74.6% of the people who use biike share are men, 23.3% are women, and 2.3% are other genders
-  young people between 20 and 30 years old are the ones who use bike_share_for_all_trip the most
- Each gender uses the bicycle at about the same average time, which may mean that the distances between the starting and finishing points are not very far.
- 18 year olds person spend the most time on bike
- men tend to use bikes less than women and other genders
- other genders use more bike_share_for_all_trip  

## Key Insights for Presentation

The main thread from this exploration is based on analysis of the relationship between the stations of departure and arrival, the duration of the journey, the information about the people who use the bikes and the types of bike.

the step that have been made are the creation of bar and pie plot to display the proportion of people according to the frequency of use by gender,
the proportion of use of the bikes by each type of people, according to the ages, the ratio with the duration of use per second and per minute,  relation between bike_share_for_all_trip and member_age, trip duration in min and bike_share_for_all_tripr, trip duration in min and the member_gender, start_station and the end_station,age and duration min, gender according to the type of bike, difference between the duration of use of bike_share_for_all_tripr,