# PyBer Analysis


## Overview of analysis
Create a new dataframe of ride-sharing data by city type with two cvs files `city_data.cvs` and `ride_data.cvs`
- Urban
- Suburban
- Rural
crating a multiple line grapgh that shows the total weekly fares for each city type. 

## Results 
The total of rides for each city type are:
1. Rural    125
2. Suburban 625
3. Urban    1625

Total of drivers for each city type
1. Rural    78
2. Suburban 490
3. Urban    2405

Total amount of fares for each city
1. Rural     4,327.93
2. Suburban 19,356.33
3. Urban    39,854.38

Total average fare per ride for each city type
1. Rural    34.62
2. Suburban 30.97
3. Urban    24.52

Here we can see a more detail datframe with a summary of the results.

![dataframe_pyber_summary](analysis/dataframe_pyber_summary.png)

Then created a dataframe creating 2 indexes type and date. To create a pivot table I removed the indexes, then created a pivot table setting the index to date, columns to typr and values to fare. Using the loc method I created another dataframe from dates 2019-01-01 to 2019-04-29 displaying the resultd by week insted of by day. Resulting int the next data frame shown below.

![wee_df](analysis/week_df.png)


## Summary

![total_fare_city_type](analysis/total_fare_city_type.png)

Some recomendations are. 
1. Invest in more urban rides, the the rages of fare don't drop 1500 weekly.
2. Review why Rural fares dont go up from 500.
3. Compare Suburban and Urban fares to know what can they do match the weekly fares.
