1) The FordGoBike Trip system
The overall goal of the presentation is to point out by visualization which of the variables of the dataset affects the trip duration, the major variables to take a look at include; the user age, gender, start station, end station and the user type. The first part of the investigation has been done and exploratory analysis was done using libraries such as pandas, numpy, seaborn and matplotlib. This is the second part of the project which presents the major findings of the first project.

- There are a total of 183412 entries in the FordGoBike dataset and a total of 4646 unique bikes. The trips in the data set have a total of 
16 variables which include:
duration_sec                  
start_time                    
end_time
start_station_id
start_station_name
start_station_latitude
start_station_longitude
end_station_id
end_station_name
end_station_latitude
end_station_longitude
bike_id
user_type
member_birth_year
member_gender
bike_share_for_all_trip

2) The data wrangling that was done on the dataset 
- Data type issues for many of the columns; end, start time to datetime and age to int type.
- Converting the member birth year to age for easy analysis and dropping empty rows in that column
- Also, dropping the empty rows in the gender column for easy analysis and drawing inference. 

3) Summary of analysis

i) After the first exploaration(Univariate)
	- Majority of the users are subscribers and a large percentage of them are Males
	- The average number of trips per minute is between 5 and 15mins with the peak estimated to be around 13mins per trip
	- The average bike trip by duration has its peak at a little above 12000 users while the trips majorly lasted in less than 1000 secs range
	- The majority of the bike users are within the age range of 20-40 years old and there is no user less than the age of 20years old.

ii) After the second exploration(Bivariant)
	- Majority of trips are from users below the age of 80 and 6000 seconds duration
	- The majority of users are between the age of 20-40 years old with high duartion of trips around the age of 30 years old.
	- The Males have a higher number of trips, however, females have longer trip duration than males.
	- The longer trips were done by Customers more than Subscribers.

iii) After the third exploration(Multivariant)

	- It can be observed from the user type and their age distribution that both Subscriber and Customer are the same regarding the trends for age and trip duration