# PyBer_Analysis

## Overview of the analysis:
The purpose of this analysis was to take the city and ride data previously provided to us and create a new summary and visualization based on city type. We first created a DataFrame of the ride-sharing data by city type, which summarized ride, driver and fare data for Rural, Suburban and Urban city types. We then created a line graph showing weekly total fares by city type for a four month period in 2019, from January 1st through April 29th.

## Analysis Results: 
### City Type DataFrame
While reviewing the DataFrame we had compiled of the ride sharing data per city type, we could see the differences between each city type as illustrated in the following table:

![Summary_by_City_Type](https://github.com/jmueller187/PyBer_Analysis/blob/main/analysis/Summary_by_City_Type.png)

This table provides the following information:
- The Rural cities had the lowest amount of rides and drivers, almost 31 times less than the Urban cities. This resulted in the lowest amount of total fares and the highest average fare per ride and per driver.
- Results from the Suburban cities showed them falling in between the Rural and Urban cities in all categories. 
- The largest amount of rides and drivers were found in the Urban cities, which resultied in the highest amount of total fares and lowest average fare per ride and per driver.

### Total Fare by City Type Line Graph
After compiling the data for total fares by city type, we were able to generate the following line chart combining Rural, Suburban and Urban cities:

![PyBer_fare_summary](https://github.com/jmueller187/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This chart provides a visual representation of the total fares for each city type over the first four months of 2019 on a week to week basis. This chart shows us the followiing:
- This chart gives us a visual representation of the Total Fares data from our City TYpe DataFrame. The highest fares per week were seen in the Urban cities, followed by Suburban and Rural cities respectively.
- Total fares in urban cities steadily increased from January through April, with three dips seen during March.
- Surburban cities reached their highest levels in the third week of February, then dropped off from March through the first week of April when they started to increase again.
- Rural cities saw the total fares run steady throughout the four month period, with the highest fares at the end of February and beginning of April.

## Analysis Summary: 
### Here are three business recommendations to address disparities among the city types:
1) Increase advertising and brand awareness in rural and suburban cities showing the benefits of the PyBer rideshare service. This would help to add more customers looking for rides and drivers looking for a driving opportunity.
2) Look for ways to attract more riders to use the PyBer service during month when revenue drops (i.e. March 2019) in order to increase ridership and total fares, such as discounted fares during lower revenue times.
3) Offer a bonus program to drivers in Rural and Suburban cities to refer additional drivers to the company and increase people looking for rides through the service. 
