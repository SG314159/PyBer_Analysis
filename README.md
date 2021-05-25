# PyBer_Analysis
Challenge 5 for UT Bootcamp - Python Matplotlib Module

## Overview
In this module, we analyze a dataset for a fictious ride-share company PyBer. The dataset contains information on 2,375 rides completed by the drivers of the company. The dataset includes the name of the city, the date/time of the ride, the fare paid by the rider, an id number for the particular ride trip itself, the type of city (urban, suburban, or rural), and the count of drivers working in that city.



## Results

#### Summary Table
The table shows the summary for total rides, total drivers, total fares, and average fare per ride and fare per driver across the three city types. 
![PyBer Chart by City Type](https://github.com/SG314159/PyBer_Analysis/blob/main/analysis/Summary_df.PNG)
Since urban areas are the most populated, it makes sense that Urban cities have the highest number of rides, number of drivers, and total fares. Urban rides had the lowest average fare per ride and lowest average fare per driver. This may be due to shorter trips within an urban city. 

Rural cities have the fewest number of rides and number of drivers, and the smallest total fare since they are less densely populated. Rural rides did have the highest average fare per ride and the highest average fare per driver. This may be due to the fact that rural rides may go over longer distances on the ground as well as there are just fewer drivers overall. It would be helpful to gather data on the distance traveled by each trip to confirm if this correlation exists.

#### Line Chart
The line chart shows the total fares earned for each week from January 2019 through April 2019.
![PyBer Chart by City Type](https://github.com/SG314159/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
Within each city type, the fare is relatively consistent across this 4-month timeframe. The total fare for suburban is about 2 or 3 times the rural total for most weeks, and the urban total fare is about 2 times the suburban fare for most weeks. All three city types had high total fares in late February, perhaps corresponding to a holiday weekend such as President's Day. Additional information about weather, events, and any other commonalities across the cities during this time would provide additional insight as to whether this pattern was related across the three city types or just coincidence.



## Summary
The total fares are highest for urban cities, followed by suburban cities, and then rural cities. If the goal is to increase total fares, consider marketing and services to improve in suburband and rural cities.
Business recommendations:
- Collect information on the distance traveled for each trip so that a clearer relationship can be understood for each city type
- Collect information on the population of each city where services exist and compare this to the driver count. Analyze how make drivers are available per 1000 people in a city to determine which cities may be underserved or overserved. Adjust driver counts as needed.
- Analyze the timestamps for ride information to determine hours of the day when demand is higher or lower. Allow drivers to access this information so that they can plan availability. 