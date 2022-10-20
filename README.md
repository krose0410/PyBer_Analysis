# PyBer_Analysis
## Overview:
After completing an exploratory analysis for PyBer, a ride-sharing business, a deeper dive into reviewing the data by city type was requested by the CEO. The scope of work includes using Python, Pandas, and Matplotlb to create a summary DataFrame and a multi-line graph of the total weekly fares for each city type: Rural, Suburban, and Urban.
## Results:
After merging two datasets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by City.

<img width="609" alt="Summary Fare" src="https://user-images.githubusercontent.com/109715441/195676887-4152f693-ea9c-4573-b937-ab6f284c459c.png">
1. The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver. The Urban drivers had the lowest average fare per ride and earned significantly less than the Rural drivers.
2. The Rural city type had the least number of total drivers giving way to having the highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type.
<img width="1027" alt="Total Fare by City Type" src="https://user-images.githubusercontent.com/109715441/195676412-7dbb60cd-814e-4515-abc5-e2ec259a5cd7.png">

## Summary & Recommendations:
1. The results of the summary DataFrame could be due to Urban city types being more compact, which collects a lower average fare per ride, while Rural city types are more spread out, which would collect a higher average fare per ride. To test this theory, PyBer should work to include mileage distance data as part of the data collection process and analysis.
2. Because there are more total drivers than total rides in the Urban city types, the Urban drivers may not have enough work to support themselves. PyBer may want to consider investing advertising dollars in the Urban city types to increase the total rides or risk losing Urban drivers.
3. If PyBer were to invest into advertising dollars in the Urban city type, the next question is when would ads be the most effective? After reviewing the Total Fare by City Tpye graph, the end of February kicks off the increase in total fares and would be a good time to launch an advertising campaign, which would also strategically help the other two city types.
