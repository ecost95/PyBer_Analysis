# PyBer_Analysis

## Overview of the analysis: 
The purpose of this anaysis was to use Pandas datafreams and matplotlib graphs in order to visualize ride data from PyBer. Specifically, we are going to:
1) Create a summary DataFrame of the ride-sharing data by city type (Urban, Suburban, and Rural).
2) Create a multiple-line chart that shows total fares per city type from January to April 2019.

## Results:

First, we created a dataframe which contained the summary of our rideshare data for each city type. In order to do this, we used the "groupby" function to group our data by "type" (Urban, Subruban, and Rural) before counting the total rides, drivers, and fares. We then found the average fare per driver/ride, and created a new dataframe which summarized our findings:
![PyBer Table](https://raw.githubusercontent.com/ecost95/PyBer_Analysis/main/analysis/SummaryTable.PNG)

Second, we created a multiple-line chart, which charts the total ride-sharing fares among the different city types from January to April 2019. The chart is in the "fivethirtyeight" style and has seperate lines for each city type.
![PyBer Graph](https://raw.githubusercontent.com/ecost95/PyBer_Analysis/main/analysis/PyBer_fare_summary.png)

## Summary: Based on the results, we have three recommendations for Pyber:
- We see that average fare per ride and average fare per driver is higher in rural areas. This is likely because trips are longer in these cities. However, there are fewer total rides in this area, so we recommend advertising more in rural cities to increase total revenue.

- In urban areas,  drivers outnumber ride requests (2,405 drivers to 1,625 rides). Therefore, we suggest that PyBer stop hiring more drivers in this area.

- In the line graph, we can see that there was an increase in fares in mid-February for all city types. We recommend that PyBer investigate the circumstances for this increase.
