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


# Deployed Tableau Analysis

# New York Citi Bike data visualizations for August 2019

From the Dashboard, we can visualize:
* Total Number of Trips: here were over 2.3 million rides for the month of August 2019.
* The Breakdown of Customer Type was: 81.1% of the users were *annual subscribers* (1.9 mln) and 18.9% were *one-time users* (443k)
* The Gender Breakdown: 65.3% *confirmed males* (1.5 mln) and 25.1% were *confirmed females* (588k), and the remainder 9.6% were *unknown* (225k).
* There is a wide range of the age of the users. Younger users tend to use the service for longer rides. (Please refer to Avg. Trip Duration to Birth Year)
* Top Ride Starting Locations are in the most touristic and busy areas, as we see here in Manhattan, particularly Midtown and Downtown.< br/>

[Dashboard2](https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book1_16172147335170/Dashboard2?publish=yes)
![](/Images/Dashboard2.png)<br />

# August Peak Hours

![](/Images/August_Peak_Hours.png)<br />
Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized. (ranging from 164,618 riders to 224,566 riders)
The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.

# Checkout times for total users
![](/Images/Checkout_Times_total_Users.png)
Bikes are mostly checked out for 4 to 6 hours.
![](/Images/Checkout_Times_Box_Whisker.png)<br />
The Box and Whisker chart gives a better visualizaition of the duration of the trips and counts.

# Checkout times by gender
![](/Images/Checkout_Times_Gender.png)<br />
Male users take approximately 3 times more rides than the female users.

# Trips by weekday and gender
[Dashboard7] (https://public.tableau.com/profile/valerie.achoa#!/vizhome/Book2_16148879896190/Dashboard7?publish=yes_)
![](/Images/Dashboard7.png)<br />

**Trips by Weekday per hour:**
- Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
- Weekend rides are highest from 10:00 AM to 7:00 PM.
![](/Images/Trips_Weekday_Hour.png)<br />

**User Trips by Gender by Weekday:**
- Those rides are mostly taken by male users
![](/Images/Heat_Map_User_Trips_by_Gender.png)<br />

# Summary
The data shows high activity of the bike sharing service in New York during the month of August 2019.
The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.
Additional analysis would be beneficial by :
- comparing data for different months to determine trends across the year,
- including weather data to find the correlation between the weather and the rides.
