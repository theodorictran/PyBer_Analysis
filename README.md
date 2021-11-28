# PyBer_Analysis

## Overview
Brought on a data analyst, I was tasked with taking different datasets and analyzing them to discover trends among three different city types: Urban, Suburban, and Rural. The goal of this analysis is to visualize the difference among city types in ride-sharing data and generating recommendations to address any differences observed. As such, I took two datasets, merged them, and created a summary table as well as a multiple-line chart.

## Results
Below is a dataframe summarizing the data by city type:

<img width="592" alt="PyBer_summary" src="https://user-images.githubusercontent.com/91519293/143784429-67eb76ff-8289-494d-ad3c-94a741396fbd.png">

By city, the dataframe presents the total rides completed, the total driver count, the total fare earned, the average fare charged per ride, and the average fare earned per driver. 

- Total Rides
  - Urban rides have the most amount of rides totaling 1625 while suburban rides have 625 rides, and rural rides have 125 rides. For perspective, urban cities completed 13 times the amount of rides that of rural cities and 2.6 times the amount of rides that of suburban cities. The differences observed between city for total rides is not completely unexpected, for urban cities have a higher population and more demand as a result.
- Total Drivers
  - Urban cities have the most drivers available while rural cities have the least amount of drivers available. Urban cities while having the most amount of rides also have the most drivers having 2405 drivers. Looking at the total rides, urban cities have more total drivers than total rides. Suburban cities and rural cities have less total drivers compared to their total rides.
- Total Fare
  - Urban cities earned the most fare at $39,854.38 while rural cities earned the least at $4,327.93. Interestingly, between urban and rural cities, suburban cities earned $19,356.33 which is nearly half that of urban cities while having less than half the amount of rides and a less than a quarter of total drivers. 
- Average Fare per Ride
  - Unlike columns before, rural cities charge more per rides on average and urban cities charge the least on average compared to other city types. Overall, the difference in average fare per ride between city types is not significantly large when factoring total rides and total drivers.
- Average Fare per Driver
  - On average, rural drivers earn the most compared to urban and suburban drivers. It must be mentioned that despite earning more average, the amount of rides in rural cities are significantly less than in urban or suburban cities. 


Below is a line chart visualizing the summed weekly total fare by city type over from January 1st 2019 to April 29th 2019:
![PyBer_fare_summary](https://user-images.githubusercontent.com/91519293/143784470-1ec4a20c-df77-4241-a8b3-64ea3ea06e5f.png)

Looking at the line chart, urban cities tend to experience more spikes in activty, especially all throughout March. All city types experience an increase weekly total fare mid-February and a sharp decline in the last week of February.

## Summary

Given the data and based on the results, I have a few business recommendations to address the disparities among the city types. For one, there is greater amount of drivers than total number of rides in urban cities. Placing a limit on the amount of drivers will lower the amount of drivers while increasing the average earnings of drivers. Urban cities will often have higher demands for drivers and rides due to attractions, workplaces, and individual needs. Howeever, suburban and rural do not necessarily bring the same demand. To increase the number of rides experienced in rural or suburban cities, its possible to lower the fare to make riding more accessible to customers. If more customers were to ride more often, then the need for drivers would increase as well adding to the driver count. Lastly, if PyBer were looking to maintain its set of drivers and their earnings, adding incentives to work in other city types is an option as well.
