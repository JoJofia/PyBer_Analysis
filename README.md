# PyBer_Analysis


## Overview of the analysis: 
This is chapter we use matplotlib library to create the visualization of data such as pivot table, scatter chart, line chart etc.
Because create the plot need put all the relative features together to give us more clear information and clarify what kind of data we want to show to our stackholder. And also we will create the summary dataframe to use groupby() function with the count() and sum() to the data from city data and ride data.


## Results:
We use groupby function to calculate the total rides, total drivers and total amount of fares for each city type.
According to the picture below, we retrieved the average fare per ride and average fare per driver from each city type.
The Urban cities have the most total drivers and highest total fares than other two cities. Although, Rural city didn't have higher amount in total fares but it had the highest in average fare per ride and average fare per driver rather than other cities.
![suammary frame](summary_frame.png)

![pyber summary](pyber_summary.png)
 
## Summary: 

### Total Fare by City Type Chart bewteen January and April in 2019
In the new DataFrame that using resample() function by week to get the sum of the fares for each week. And it gave us distinct the different bewteen Urban, Suburban and Rural. According to the weekly fare in each city, we can saw the Urban city has more effective in transportation. On the opposite, the Rural city has the highest fare on ride at $34.62 that cause less worker go to this city.
1. Potential opportunity on Rural city and Suburban city is to hire more drivers for those two cities or expand the different kind of bussiness in the local city. 
2. The average fare charge for each driver in Urban city is $16.57.However, this market graudally become saturation. we can relocate the drivers to other cities or different job area such as food deliver, package delivery etc to give more support to increase the overall revenue per driver.
3. Do the increase or decrease on the fare base on the QTY of riders in the city.
![PyBer fare summary](PyBer_fare_summary.png)


