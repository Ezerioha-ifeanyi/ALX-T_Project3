# Ford gobike Data Exploration
## by Ezerioha Ifeanyi Emmanuel

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

I converted several variables to a correct datatype (start_time, end_time, start_station_id,bike_id, user_type). And created several additional variables (start_day, end_day, start_day_of_week, end_day_of_week, start_hour, end_hour) to be able to create plots with different time resolutions.



## Summary of Findings

In the exploration, there are lot of insights that i found out. They are:

- Further I learned that that the distribution of starting a bike trip is bimodal: most trips start between 8-9 or between 17-18 o'clock.
- Customers have as busy hours for starting their bike trip after 7am and also after 3pm and before 6 o'clock. 8am and 5pm is a busy hour of the Subscribers.

- Subscribers mainly hire a bike during weekdays (more than double the level of weekends), 
and Customers hire especially in the weekend.

- The bike trip duration of Customers is about the double of Subscribers (22 vs 10 minutes).
A significant higher trip duration during weekend days by Customers. 
The duration is about 27.5 minutes during weekend days, which is about 10% higher than the highest score during a weekday.

- For both types of users the distribution of rides during the weekdays depends a lot on the hour of the day and day of the week.

- It is interesting, that Customers tend to use the bike service mostly on Thursday/Friday from 8AM to 5 PM, while Subscribers will likely have a trip from Monday to Friday during rush hours (7-9 AM, 16-18 PM).





## Key Insights for Presentation

For the presentation, I focus on the distribution of users by `Gender`, I then decided to know 
which `User_type` dominates the most by plotting the distribution of Users by User_types. 

Afterwards, I did a horizontal barplot of start_station_name to check for station most
used by users. I also decided to know the distribution of end_hour of trip for users of Ford gobike.


