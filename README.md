# PyBer_Analysis

## Overview
Each year ridesharing services are growing in popularity and are becoming a common norm amongst society. These types of services benefit not only the riders, but drivers as well, across the world. 
In order to grasp the market for these services, we must conduct a market analysis. This  helps companies understand consumer behavior and economic trends. PyBer is an example of a ridesharing company and an analysis of their ridesharing data is below. 

### Purpose
The purpose of this analysis is to not only understand ridesharing usage in the three city types (urban, suburban, and rural), but also to evaluate the relation between the number of riders and drivers by city type and the impact it has on fares. The overall analysis and visualizations, of data from the first third of 2019, will assist with how PyBer can strategically expand its services and to determine cerntain affordabilities to ridesharing services. 

### Resources Utilized to Complete Analysis

CSV Files: city_data.csv, ride_data.csv
Jupyter Notebook Files: PyBer.ipynb, PyBer_Challenge.ipynb
Python 3.7.6


## Results

### Overview of City Types
The bubble chart below displays the relationship between city type (urban, suburban, rural) and the total number of rides per city, the total number of drivers per city and the average fare (USD $) per city. The circle size realtes with driver count per city.

![Fig1](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig1.png)





### Ride Counts by City Type

Ride counts by city type is expressed using a box-and-whisker plot and a pie chart. The box-and-whisker plot shows that the urban ride count data includes an outlier with 39 rides in one city. In rural cities, the average number of rides is approximately 4 times lower than urban cities and 3.5 times lower than suburban cities. The pie chart conveys similar information, with each pie wedge representing a city and the percentage of its total rides. Urban cities have the highest percentage of total rides with 68.4% of rides, whereas suburban cities have 26.3% total rides and rural cities have 5.3%

![Fig2](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig2.png)
![Fig6](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig6.png)

### Driver Counts by City Type
Driver counts by city type is expressed through the number of drivers per city type and the percentage of total drivers by city type. On average, the number of urban drivers is 9x higher than the number of rural drivers and the number of suburban drivers is 4x higher than the number of rural drivers. The data does not show any outliers. The pie chart shows that urban cities have the highest percentage of total drivers with 80.9% of rides, whereas suburban cities have 16.5% total drivers and rural cities have 2.6%

![Fig4](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig4.png)
![Fig7](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig7.png)

### Fare Counts by City Type
Fare counts by city type is expressed through the number of fares per city type, the percentage of total fares by city type and the total weekly fares for each city type. The box-and-whisker plot does not reflect any outliers. However, it does reflect that the average fare for rides in rural cities is higher ($36) than those in urban cities ($25) and even suburban cities ($31). Ridesharing pricing models are based on supply and demand and when the demand for rides exceeds the supply of cars, the fare price increases. This explains why the average cost of rides in rural cities is higher. The pie chart shows that urban cities have the highest percentage of total fares with 62.7% of rides, whereas suburban cities have 30.5% total fares and rural cities have 6.8%. The multiple-line graph shows total weekly fares for each city type. Overall, urban cities have the highest revenue in comparison to suburban and rural cities. Riders are most concentrated in dense urban areas, so this could explain why the sum of the fares for each week in urban areas is highest. Interestingly, fares proportionally increased across city type in the second half of February. 

![Fig3](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig3.png)
![Fig5](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/Fig5.png)
![PyBer_Fare_Summary](https://github.com/DannyJohnson-Hi/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png) 

## Summary
Based on the results, the following recommendations can be made to address disparities found amongst the city types.
1.	The analysis could increase in benefit by having additional data points that run across the year, instead of focusing on just the first third of the year. Additional data could provide insights into yearly trends and can be used to forecast ride, driver and fare counts by city type for the following year.  
2.	inclduing an analysis on the usage and demographics (e.g. age, gender, race) of the riders could provide further insights on different characteristics of a population. Having this data could prove to be useful in understanding consumer behavior, so that the brand can be appropriately marketed and developed, to target the specific demographic environment.   
3.	Offering incentives to maintain loyal riders and drivers. This will help drive business and strengthen relationships with existing riders and drivers. 





