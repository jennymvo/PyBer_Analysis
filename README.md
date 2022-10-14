# PyBer_Analysis

## Overview of Project
The project consists of using pandas dataframes and matplotlib to create a summary of the ride-sharing data from different city types, and to create a multiple-line graph showing the total fares per week for each city type in a range of dates.  

## Results

![Summary of Ride-sharing data in city types](https://github.com/jennymvo/PyBer_Analysis/blob/main/images/summary_df.png)

To determine the average fare per ride and driver of each city type, the total rides, total drivers, and total fares were first determined then the values were used to calculate the average fares. 

Urban cities were found to have the highest total fares compared to suburban and rural areas, and also the highest number of rides and drivers. However, the average fare per ride and driver were the lowest among the list. 

In contrast, rural cities have the lowest total fares, rides, and drivers but the highest average fare per ride and driver.

Data from the suburban city type nearly centers in the ranges for rural and urban city types. 

![Total fares by city type through Jan - April 2019](https://github.com/jennymvo/PyBer_Analysis/blob/main/images/line_chart.png)

To see the trend of the total fares throughout January and April of 2019 for all three city types, the data of each ride was binned to weeks, then the data was plotted on a line graph with the weeks on the x-axis and the total fares for those weeks on the y-axis. 

The trends of fare totals for each city type is consistant, with rural having the least amount of fares, urban with the highest amount of fares, and suburban having a middle amount of fares. 

There is a clear trend for all three city types in Feburary, where there is a slowdown of fares to the middle of Feburary and then a sharp spike of fare totals for all three city types at the last week of Feburary. 

At the end of April, there is increased fares in suburban areas but there is a decrease in rural and urban areas. 

## Summary

As a summary, some business recommendations for the CEO:
1. As there is a high demand for rides in urban cities, the drivers are earning less per ride. I suggest increasing the fares in this area so the drivers can earn more per ride.
2. In rural cities, even though the drivers are earning more per ride in comparision to urban cities, there is not much demand for rides. Possibly want to increase marketing in these areas for increasing demand, or creating some kind of incentive.
3. For the trends in decreases of fares in each city type throughout the year, incentives should be implemented, especially pertaining to the first half of Feburary, and for rural and urban areas at the end of April. 