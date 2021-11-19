# Ford GoBike Analysis Project

If you live in San Francisco, you have probably noticed the plethora of bikes and electric scooters. Now, Motivate is expanding the Ford GoBike program in San Francisco to include pedal-assist bikes.These bikes work by giving the rider a bit of a power boost while pedaling. Currently, there are 262 Ford GoBike stations with 2,600+ bikes across the San Francisco Bay Area.

Throughout this project, we'll be specifically looking at data related to Ford GoBike. We'll look at gleaning some insights across several observations and looking at them with some data visualizations.

## Dataset
In this Udacity project, we'll be taking a look at some data provided to us by Ford's GoBike project. Ford has kindly made this data available to us [at this provided URL](https://www.fordgobike.com/system-data).

The data including and the dataset can be found in the [at this provided URL] (https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).
```
 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender
```

## Summary of findings
 - In the exploration, I found that In gender I have male, female and other but others didn't make any sense in a real life so i decide to make it out of my data due to it didn't a significant in results and males is much more than females

 - User Type is an important characteristics in our data and other data depend on it so we must to know the numbers and percentage of customers and subscribers, we can see that subscribers is much more than customers and Customers have consistently longer trips across all hours of the day. However, customer trips are much longer at midnight and midday.

 - The most trips duration is smaller than 20 minutes and the peak(the most time takes) around (4 - 10) min. The average trip duration is 8.4 min and, ages of the most common users who had a ride is between (25 - 40) years No users less than 20 years old Low users between (45 - 80) years.

 - The Most station Frequently from the top 20 most visited stations. The most stations Frequently to start are Market St and San francisco caltrian station 2 and (San Franscisco Ferry Building) had a wider distribution of ride durations.

 - Tuesdays and Wednesdays are the most frequently days , however Thursdays, Mondays and Fridays are very close to the Tues/Weds numbers , saturday and sunday are not popular as the rest of days.

 - The high frequently during the morning hours of 8-9 AM, and in the afternoon hours of 5-6 PM The most day have trips is thursday as we known it is weekend so it have high number of tips. The most days has long duration is saturday and sunday and less days is tuesday and wednesday


## Key Insights

 - **Gender has no real effect on ride duration.** One might expect that males would be taking the longest rides, but the data doesn't indicate this at all. Across all ages, the differences between duration of male riders vs. female & other riders is negligible. In fact, it wasn't uncommon that females and those who marked their gender as "Other" would often ride longer than male riders.

 - **User types have effect on ride duration and the No. of rides through the day.** There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and occasionally around lunch time. Customers are usually tourists who use the system mainly on weekends and higher percentage of customers are taking longer trips then compared to subscribers

 - **Timing (date and time) of start rides has much effect on duration and No. of trips** depending on the day if it was a rest day, weekend or weekday as we known it is weekend so it have high number of trips and the time if was in the morning hours of 8-9am, and in the afternoon hours of 5-6pm. This might be related to the time for work and school

 - **Ages has effect on ride duration.** The older the users, the less time they will ride

## Files Included

Here's a brief description of all the files at are available as part of this project.

 - **FordGobike-exploration.ipynb**: This jupyter notebook is where we do all the exploration of the data to be used in our explanatory analysis and slides later.
 - **fordGobike-explanation.ipynb**: This jupyter notebook synthesizes the information gleaned from the exploration notebook and will be the foundation for the slide deck down below.
 - **fordGobike-explanation.slides.html**: And finally, this is the slide deck that is built off the jupyter notebook above.

## Tech Stack

These are the following packages I used throughout this project.

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

```

