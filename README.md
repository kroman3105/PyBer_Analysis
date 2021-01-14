# PyBer Analysis

## Overview of Project
We were directed by PyBer's CEO to create a summary DataFrame of the ride-sharing data by city type.  Once created, we will then use the tools at our disposal (ie. Pandas, Matplotlib) to create a multiple-line graph showing total weekly fares for each city type.  Our objective is to use this data to show the differences that exist between city types, in order to help PyBer leadership make informed decisions when dealing with all types of cities.

## Results
The summarized findings from our analysis can be found below: 

![DataFrame_By_Type](https://github.com/kroman3105/PyBer_Analysis/blob/main/analysis/DataFrame_By_Type.PNG).  

The DataFrame revealed the following results:

 - Urban cities had the highest number of rides at 1,625 while Rural cities had the least at 125
 - Urban cities had the highest number of drivers at 2,405 while Rural cities had the least at 78
 - Urban cities brought in the most total fares at $39,854.38 followed by Suburban at $19,356.33 and Rural at $4,327.93
 - Rural cities brought in the highest fare per ride and per driver at $34.62 and $55.49 respectively.  Suburban cities brought in $30.71 per ride and $39.50 per driver while Urban cities brought in only $24.53 per ride and $16.57 per driver

In addition to the above summarized data, the below chart shows the total weekly fares brought in for each city type:

![Weekly_Fare](https://github.com/kroman3105/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

- All city types experienced a surge in fares in late February
- The suburban fares brought in began to grow rapidly throughout April, will the other city types experienced declines in their fares

### Conclusion
The data shows us that we are bringing in over three times as much per driver in the rural cities as we are in the urban cities.  One recommendation would be to start a campaign to bring on more drivers in these rural areas.  In turn, this could lead to more rides in those areas and drive up the total fares collected.  On the flip side, the Urban areas have more drivers than rides which means there were several drivers who didn't give a single ride over the period analyzed.  For the urban areas, we think it would be more beneficial to target campaigning efforts to track down more riders.  There are plenty of drivers to accomodate them, we just need to make sure word is getting out about the service.  Finally, it would be good to invest some time and effort to understand what circumstances were in play at the end of February that drove across the board surges in total fares.  If demand was high during this period, it may be a good time to increase the fare per ride to further increase the total revenues.
