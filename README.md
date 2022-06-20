# PyBer_Analysis

## Overview
Analyze and visualize PyBer ride-sharing data using Python, Pandas and Matplotlib, to help the company improve access to ride-sharing services and determine affordability for underserved neighborhoods. Using the data provided, I created a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type for V. Isualize. The following information is a written report that summarizes how the data differs by city type and how those differences can be used at PyBer.
The analysis is based on the following points among the different city types:
- the percentage of total rides,
- the percentage of total drivers,
- the percentage of total fares,
- the average fare per ride and driver,
- the total fare by city type.

## Resources
Data Source: city_data.csv, ride_data.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results
In three of the 5 category columns in this data frame (Total Rides, Total Drivers and Total Fare), Urban cities ranked the highest in these categories, followed by Suburban and then Rural cities. However in the final 2 categories (Average Fare per Ride and Average Fare per Driver), we saw the inverse, with Rural cities ranking the highest and Urban cities the lowest. We can see that the Urban cities have the most number of people driving for Pyber or using their services, resulting in the high revenue number in the Total Fare column. The completion from other ride-sharing services may also push Pyber's rate in Urban cities down, which is why they came in last in the Average Fare per Ride and Average Fare per Driver columns. Rural cities may have fewer options for a ride-sharing service, which is why Pyber can charge more there. However the low number of drivers and customers in Rural cities may be due to the fact that more people own cars in Rural areas as opposed to Urban ones.

<img width="595" alt="df_summary" src="https://user-images.githubusercontent.com/88937178/133907657-5ef9ecf1-cecc-4ab4-a64b-a08372fa305a.png">

## Summary
I would recommend the following business recommendations to Pyber to address the disparity among city types.
1. Reduce the fare rate in Rural cities and see if it encourages more people to use Pyber
2. Provide discount or other incentives to increase the number of riders in Rural and Suburban cities.
3. Increase the cost of rides in Urban cities in order to bring up the Average Fare per Ride and Average Fare per Driver.
