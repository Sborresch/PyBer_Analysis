# PyBer_Analysis
# Overview
I was recently hired as a data analyst for a python based ride-sharing company, called Pyber. My first major assignment was to determine the accessability and affordability of Pybers services to each major city type, rural, suburban, and urban. Going forward, Pyber has plans to provide improved accessability and affordability for those populations who are underserved.

In order to determine which populations are classified as underserved, I needed to explore a large CSV dataset that displays ride, fare, driver, etc. information. Once this data was explored, organized, and pseudocoding was written, I can use Jupyter Notebook, Pandas, Python, and Matplotlib to run programming code to determin patterns and trends based on the Pyber data. Once these patterns and trends are determined, visualizations can be created that will be distributed to the leadership team for review on which direction to take Pyber to better serve the underserved populations.

Below are the results and reccomendations of the Pyber initiative of improved accessability and affordability for underserved populations. To access the files for this analysis please see below links:
- [city_data.csv](https://github.com/Sborresch/PyBer_Analysis/blob/main/Resources/city_data.csv)
- [ride_data.csv](https://github.com/Sborresch/PyBer_Analysis/blob/main/Resources/ride_data.csv)
- [Pyber_challeng_syntax](https://github.com/Sborresch/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

# Results
## Summary Dataframe
![Screenshot](https://github.com/Sborresch/PyBer_Analysis/blob/main/summary_dataframe.png)
### Difference Among City Types
This dataframe is a visualization tool that shows some metric (total rides, drivers, fares, etc.) and its values at one specific point in time. This dataframe provides a clear snapshot of how Pyber is performing in each of the three city types rural, suburban, and urban.

According to this dataframe, urban city type Pyber experiences have the highest count of total rides, total drivers, and total fares. This is likely due to the high demand of urban dwellers relying on public transportation and ride-sharing companies like Pyber because they do not own private transportation. This can be due to a financial or space issue. However, the average fare per ride is cheaper in urban city types versus suburban and rural. It is likely that although there may be more frequency in urban fares, the suburban or rural fares take a longer time to complete. This produces a higher fare cost for the rider and equates to a higher fare per driver. Therefore, both the rider is paying more and the driver is making more money. The findings from this summary database follow traditional demand and supply curves found in basic economic teachings. I see no abnormalities with this dataframe and believe it is a healthy distribution for performance and profit for Pyber.

## Multiple-Line Chart
![Screenshot](https://github.com/Sborresch/PyBer_Analysis/blob/main/PyBer_fare_summary.png)
### Difference Among City Types
The multiple-line chart is a visualization tool that shows some value and how it performs over time. In comparison to the summary dataframe, this shows more longitudinal data versus a value of some metric at one point in time.

Based on the above image, the total fare values for all three city types are in their own independent ranges. There is no overlap between the total cost or fare for rides between any city type. This clearly shows that the most expensive fare rides are apparent in the urban city type, followed by suburban, followed by rural. This can inform the data analytics team that there is likey a higher quantity and average fare cost for riders being transported in urban areas. This is likely because riders in urban areas typically do not own transportation vehicles, thus relying heavily on the public transportation or ride-sharing companies. In addition, because there is clearly a demand in urban areas due to low vehicle ownage rates, the ride-sharing companies can change a higher price in cases where the demand is larger than supply. This is typically known as surge pricing and also is found during specific times of the day, such as rush hour as riders travel to and from work. As the city type becomes more distant from the hot demand market in the urban environment, the total fare for transportation decreases. More individuals are likely to own private transportation to navigate their surroundings, as most things are spread out. Out of necessity, these individuals purchase and insure private vehicles, thus removing them from the ride-sharing funnel in most cases. This graph clearly details how demand drives total fare price because of the need variance in different city types.

# Summary
The goal of this data analysis was to identify how Pyber is used among each of the city types. Once Pyber was aware of its current situation, it can navigate to where it wants to be which is to provide improved access and affordability for underserved populations. In this case, those riders in rural and suburban city types. Below are the recommendations I determined to help Pyber reach it goals.

## Recommendation #1: Decreasing Fare Rates for Rural and Suburban Riders
Based on the summar dataframe rural and suburban riders are charged 5 to 26-41% higher than urban riders. This can likely be due to the amount of time or distance the driver must provide each rural or suburban customer. If Pyber is looking to make their services more affordable to the underserved popoulations of rural and suburban individuals than decreasing the rate of which they are charged might increase customer satisfaction and demand in these areas.

## Recommendation #2: Increasing the Availability of Drivers in Rural and Suburban Locations
Based on the summary dataframe there are less drivers than there are riders in both rural and suburban city types. This can increase wait times for riders and makes supply limited thus increasing the price per driver. In comparison, there are nearly double the amount of drivers than riders in urban areas. Therefore, there is more accessability to riders in urban areas than there are in others. Because the rural and suburban areas are underserved it can be an option to increase the amount of drivers employed by Pyber to better fulfill the demand.

## Recommendation #3: Both Decrease Fare Rates and Increase Availability of Drivers in Underserved Locations
If Pyber really wants to cater to these underserved markets, than one drastic plan is to make a small decrease in the fare ride rates and make a small increase in the amount of drivers in these areas. This will help narrow the gap of disparity amoung the populations by adjusting two important factors, price and supply. 
