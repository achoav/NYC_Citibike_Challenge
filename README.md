# NYC_Citibike_Challenge
# Project Overview
This project is an analysis of New York Citi Bike data for the month of August 2019, using data visualization tools to explore the viability of a bike-sharing business in Des Moines.

# Resources
**Data Source:** Citi Bike Data, 2019-citibank-tripdata.csv < br/>
**Software:** Python 3.8.5, Anaconda Navigator 1.7.2, Jupyter Notebook 6.3.0, Tableau Public 2021.1.0

# Deliverable 1
Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype without index (index=False).  The new column created is named Tripduration Datetime. The code is on file named [NYC_CitiBike_Challenge.ipynb] (https://github.com/achoav/NYC_Citibike_Challenge/blob/main/NYC_CitiBike_Challenge.ipynb)

## Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:

*	How long bikes are checked out for all riders and genders.
	a.	What is the Breakdown of Annual Subscribers vs. Short-Term customers? From the pie chart you can see that the majority 81.1% (1,900,359 ) are subscribers and one-time riders are 18.9% (443,865).
	b.	What is the Gender Breakdown of Active Riders? Male riders are 65.3% (1,530,272), Female 25.1% (588,431) and unknown 9.6% (225.521)
*	How many trips are taken by the hour for each day of the week, for all riders and genders. The horizontal column graph illustrates that the peak hours are from 5pm to 7pm (ranging from 164,618 riders to 224,566 riders).  And the off-peak hours are from 2am to 5am (suggested bike maintenance services to be performed).
*	A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
Results

*	What is the Breakdown of Annual Subscribers vs. Short-Term customers? From the pie chart you can see that 443,865 (19%) are one-time customers and the majority 1,900,359 (81%) are subscribers.

*	What are the Peak Hours for Bike Rentals? From the Horizontal Column chart, peak riding hours are from 5:00pm to 7:00pm.   And, low peak hours are 2:00am to 5:00am when bike maintenance services should be performed.
*	What are the Top Bike stations in NYC to Start a journey?
*	What are the Top Bike stations in NYC for Ending a journey?
*	What is the Gender Breakdown of Active Riders?
*	What Is the Average Trip Duration by Age? The later the birth year, the longer the ride duration, i.e., younger riders tend to use the bikes for longer periods of time.
*	Which Bikes Are Most Likely Due for Repair?
*	How Variable Is Bike Utilization? These will allow us to view the total usage time per bike, as well as which bikes are used the most frequently, which will give us insight into which bikes may need repairs.

# Deployed Tableau Analysis
## Links to dashboard

[Dashboard2 Book 1](https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book1_16172147335170/Dashboard2?publish=yes)

[Dashboard2 Book2] (https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book2_16148879896190/Dashboard2?publish=yes)
[Checkout Time by Gender] (https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book2_16148879896190/CheckoutTimesbyGenders?publish=yes)
[Dashboard4](https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book2_16148879896190/Dashboard4?publish=yes)
[Dashboard6] (https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book2_16148879896190/Dashboard6?publish=yes_)



# New York Citi Bike data visualizations for August 2019

From the Dashboard, we can visualize:
* Total Number of Trips: here were over 2.3 million rides for the month of August 2019.
* The Breakdown of Customer Type was: 81% of the users were *subscribers* (1.9 mln) and 19% were *one-time users* (443k)
* The Gender Breakdown: 65.3% *confirmed males* (1.5 mln) and 25.1% were *confirmed females* (588k), and the remainder 9.6% were *unknown* (225k).
* There is a wide range of the age of the users. Younger users tend to use the service for longer rides. (Please refer to Avg. Trip Duration to Birth Year)
* Top Ride Starting Locations are in the most touristic and busy areas, as we see here in Manhattan, particularly Midtown and Downtown.
[Dashboard2 Book 1](https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book1_16172147335170/Dashboard2?publish=yes)
![]Images/Dashboard2.png

# August Peak Hours


Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.
The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.

# Checkout times for users


Bikes are mostly checked out for 4 to 6 hours.

# Checkout times by gender


Male users take approximately 3 times more rides than the female users.

# Trips by weekday and gender
 

Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
Weekend rides are highest from 10:00 AM to 7:00 PM.
Those rides are mostly taken by male users.

# Summary
The data shows high activity of the bike sharing service in New York during the month of August 2019.
The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.
Additional analysis would be beneficial by :

comparing data for different months to determine trends across the year,
including weather data to find the correlation between the weather and the rides.
