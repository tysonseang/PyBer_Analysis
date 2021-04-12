# PyBer Analysis
For this analysis, Python, Jupyter Notebook, Pandas, and Python's two-dimensional plotting library, Matplotlib were used to inspect data, merge data sets, perform calculations, and create multiple data series and data frames. Data was then visualized in the form of various line, bar, scatter, bubble, pie, and box-and-whisker plots.   

## Overview
PyBer, a python-based ride-sharing app company, wanted to analyze access and affordability for ride-shares in rural, suburban, and urban cities. For this research project, the [city_data.csv](Resources/city_data.csv) file, which tracked driver counts across various cities and city types, as well as the [ride_data.csv](Resources/ride_data.csv) file, which tracked rides by city, date, fare, and fare id, were used as source files. 

Python scripts using Pandas libraries, Jupyter Notebook, and Matplotlib were used to transform this data into a variety of charts that showcase the relationship between the type of city and the number of rides and drivers, as well as create a line chart that shows the total weekly fares for each city type.

## Results

As seen in the DataFrame below, ride-sharing data varies widely across the three city types analyzed. Among the city types, rural locations saw the lowest number of rides, drivers, and total fares. This resulted in the highest average fare per ride and the highest average fare per driver. In contrast, urban cities saw 13x as many total rides, more than 30x as many drivers, and 9x the total fares. The average fare per ride in urban cities was roughly $10 lower than in rural cities  while the average fare per driver was nearly $40 lower.  

![PyBer_fare summary DataFrame](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/PyBer_DataFrame_summary.png)

Weekly total fares analyzed from January through April 2019 indicate that the total number of urban fares outpaced suburban fares week-over-week. Likewise, suburban fares outpaced total fares in rural cities each week during the time period. 

![PyBer_fare_summary Over Time](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Scatter plots were created to analyze relationships between total rides, averages fares, and driver counts for each city. 

![PyBer Scatter by City Type](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/Fig1.png)

Pie charts were also created to visualize the percentage breakdown of total fares, total rides, and total drivers by city type.

![Percent of Total Fares by City Type](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/Fig5.png)

![Percent of Total Rides by City Type](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/Fig6.png)

![Percent of Total Drivers by City Type](https://github.com/tysonseang/PyBer_Analysis/blob/main/analysis/Fig7.png)

## Summary

Based on the results, three business recommendations were provided to PyBer's CEO in order to address the disparities among city types. 

- Rural drivers represent only 2.6% of PyBer's total drivers by city type. This is resulting in a lack of ride accessibility for app users in rural areas. The average number of drivers in rural cities (4.3) is also roughly 3- to 8.5-times lower than suburban (13.7) and urban (36.7) cities. A marketing campaign focused on boosting rural driver sign-ups could improve this discrepency. 
- Despite only representing 5.3% of PyBer's total rides by city type, rural fares account for 6.8% of PyBer's total fares. This could be a result of longer trips in rural areas. Additional analysis of average trip lenghts is needed. 
- Lastly, total fares in USD largely followed similar patterns during the time period analyzed, regardless of city type. A noticeable spike was seen across all three city types during the end of Februrary. Additional research is needed here to determine causality. 
