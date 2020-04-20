# Ford GoBike System Data

## Dataset

his data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
Data was pulled from location: https://www.lyft.com/bikes/bay-wheels/system-data



## Summary of Findings

* Bike usage is reduced sligghtly during winter months like November, December, January and February.
Peak is in July and October in the year 2019.

* Based on one year data of 2019 - Weekdays are busier than weekends. That can be due to working folks using the bike as part of their commute.
* Based on one year data of 2019 - rush hours are 7am to 9 am . Evening 4pm to 7pm. Peak hour is 8 am and 5 pm. Again, we can attribute this to being used by working people as part of their commute
* For the duration analysis, it looks like most of the ride was between 8 to 16 minutes
* Overall usage by customers is always less than subscribers. Customer usage is more on weekends, which suggests, customers could be occasional visitors visiting the city. Their usage is also more on Saturday and Sunday. On the other hand, subscribers are regular users who use it for daily commute purposes. Bike usage from them is more on weekdays. Weekends their activity is significantly less.
* Interestingly, bike usage duration is almost the same irrespective of customers or subscribers. Their popular usage time is between 6 to 12 minutes. This suggests that people use a bike for short commutes like Subscribers might take the bus or train and then take the bike from station to their final destination. For customers, they could be using a bike as hop and go to visit multiple destinations while touring the city
* San Fancisco is the location where bike ride is heavily used, followed by Bay area and then San Jose.
* Again, there is no significant difference in trip duration irrespcive of city. For customers, majority of th eusage is between 8 to 12 minutes. For subscribers, majority if the usage is between 6 to 10 minutes


## Key Insights for Presentation

For the presenation I focus on answering these questions:

* When are most trips taken in terms of time of day, day of the week, or month of the year?

* How long does the average triptake?

* Does the above depend on if a user is a subscriber or customer?

I start by focusing how the bike usage is impacted by Day, Month and Hour.

Afterwards, I introduce each of the categorical variables one by one. To start,
I introduced user_type and plotted by cluster bar chart.  The other two categorical
variable i used was location area. I used line plot to see how bike usage was impacted i
n different geographical location. I've made sure to use different color palettes for
 each location variable to make sure it is clear that they're different between plots.
 I have also used cluster bar chart and violin chart to show the same information.
