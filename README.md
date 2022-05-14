# PyBer_Analysis

## Overview of Analysis

The purpose of this analysis was to create a raport that showcased how the data between city types differs for ride-sharing. This analysis aimed to compare Suburban, Urban, and Rural city types and the fares recorded for each. For this Analysis, I used Python, Pandas, and Mathplotlib to create a data chart, specially used to create a multi-line graph and used Python and Pandas to create a DataFrame centered around weekly fares for each city type.

## Results

### Ride-Sharing Summary DataFramy by City Type

In the first analysis, the scope of work included creating a Pivot table that seperate City Types' into 5 different columns of information. Based off this analysis, Rural city types had significantly lower counts of Total Drivers at 78 compared to Suburban and Urban. The Average Far per Ride and Average fair per Driver was also the highest of the 3 types for Rural. The total rides shows a smaller frequency of use for rural at 125 rides, compared to the Urban City Type who had a total of 1625 total ride. In comparison, Urban city types had the most amount of drivers at 2405, with Average Fair per Ride and Average Fare per Driver at the lowest cost of all three city types.

<img width="418" alt="City Types Deliverable 1" src="https://user-images.githubusercontent.com/102635884/168447519-dfb931a3-1a92-4367-baec-36d1349eed83.PNG">

### Total Fares for Each City Type

Using the Multi-line graph to see city types grouped by weeks, the analysis shows that between the months of Feburary and March, all 3 city types saw peaks in ride-sharing usage. This graph is also similar to the pivot table by providing a visual to quickly see that Urban City types has the highest Fare totals and the highest usage, this can likely be due to a higher amount of drivers and a lower average fare per ride compared to the other 2 city types. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/102635884/168447701-4984e4e6-82af-480f-a322-7ea438128db3.png)

you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Summary and Recommendations:

Based off this analysis, there are three recommendations that PyBer could consider when making decisons amongst disparities for different city types

1. For rural city types, the average fare per ride is the highest of all the city types. A possible factor is that with the low amount of drivers available, there is a higher demand in the area causing a higher price. A recommendation would be to recruit more drivers in these areas. Rural city types see the same amount of peaks as Urban city types do, but due to the high cost and low amount of driver's it does not capitualize on that market as much as it has potential to do so. 

2. Urban city types have a significantly larger amount of drivers than the other 3. This can cause a compettion between drivers and potential lose in the amount of drivers if there is not enough opportunities for them to drive. Urban City types had 5 different periods where they experineced a peak. With large amount of drivers, it would be ideal to keep a steady flow in the amount of people using ride-sharing. A way to increase work for drivers and maintain a steady flow of income coming in from fares is to create more deals or incentives for PyBer customer's to use ride-sharing. This will drive up usage for the year if they are especially targeted during the time periods where the company does not see peaks in usage. 

3. Currently the company does not use mileage in it's data collection. If Pyber were to record information on the mileage of customer's request it would be able to track the distance that their customers are traveling. If they see that in Urban city types, all travel is local and nearby to one another, it could implement a ride-sharing option where a driver could pick up more than 1 customer at once, which would reduce the travel for the driver, reduce pricing per customer slightly, but also add a second passenger, leading to a possible increase in fare collected.    
