# PyBer_Analysis

## Overview of the analysis
Our team's manager gave a new assigment. We are to analyze and present in a chart the data of a ride-sharing company (PyBer) by city type.
City type, in this analysis, is divided between "zones"; Urban, Rural, and Suburban.
We were given two datasets, city_data and ride_data.
We merged the two sets to create a merge dataframe based on the city (name) and with the city type as the Index (as it's the main part of this analysis).

## Results

### Fares weekly by city type
As we detailed the merged Dataset, we looked at the total weekly fares by city type.
Along the way, we also looked at other variables of the dataset that could be used for further recommendations and deeper analysis.

As far as the weekly fares, we can see that the Urban city type is the one with the most fares (in $USD), and consistently across all weeks.
![image](https://user-images.githubusercontent.com/75656368/200149749-563cbb1f-7896-4beb-aa29-8a636b5dcbd2.png).

Then comes the Suburban fares, and finally the Rural Fares.

However, in order to understand further and make accurate recommendation, we must not only look at weekly fares.

### Other elements of analysis
When we look at the dataset, the weekly fares is higher in Urban city types. But it's also where there are most drivers and more rides volume.
If we look at the first dataframe created, we can see that the average fare per ride is higher in Rural area, with less drivers. But only very few drivers.

![image](https://user-images.githubusercontent.com/75656368/200150065-e35f931c-349c-46a6-8d6d-7a71feb508f9.png)


## Summary

### Recommendation 1: Based on final chart  
Given that the Urban area is the one bringing in the most revenue (based on fare), we should focus most of the marketing budget and get more driver in the market to service the high number of ride requests.

### Recommendation 2: Deepeer understanding of the current data
We should look at the day of the week where each city type peaks. At the moment, we can see that the fare revenue peaks in spring and is relatively lower in the winter.
But we should look at the time of the day the ride started as well as the day of the week (Day_name).
From there we should be able to recommend when would more driver need to be available.

### Recommendation 3: Obtain more data
We recommend to obtain ride details. Starting with end time of the ride and number of passenger.
We would like to determine the avg fare by city type by passenger. 
Additionally, we would like to get the distance travelled per ride.
From there, we should get better customer behavior data and market each city type to the drivers that prefers or to do less mileage but more passengers, or to do more mileage with less passenger, etc.

