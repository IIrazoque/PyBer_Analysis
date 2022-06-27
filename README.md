# PyBer_Analysis
### Overview of the analysis

Since PyBer’s Ride Sharing App Company has been launched in 2019, the following analysis will help improve access to ride services and determine affordability for underservice neighborhoods. We gathered statistics on drivers , rides, and fares based on city types.

# Results
### Overall PyBer Statistics 
We create a dataframe displaying total rides, driver and fares based on city types. Averages for each city were also calculated. As shown in figure A, we see automatically see higher ride demands in urban areas compared to rural areas. Interestingly there is almost double the drivers to rides in urban areas. This leaves many drivers without fulling rides if they the demand remain high. The opposite could be true if rural areas had higher demand but not enough drivers, hence the higher fare rates per driver. 

*Figure A - PyBer Summary Dataframe*

![This is an image]
 
A bubble chart was also created displaying the total number of rides per city and their average fare. We can also see urban driver’s fulling more rides as this correlate to the circle size per city. As seen in rural areas “yellow” circles, drivers are a lot higher in fare rates yet set lower in ride counts.
*Figure 1 - PyBer Ride-Sharing Data 2019*

![This is an image]
 
## PyBer Driver Statistics
Driver counts are displayed below in the boxplot chart along with percentage of Pyber drivers in the pie chart. In the boxplot we see min, max, and averages of each city drivers. Again to show the demand of drivers in rural areas (2.6%) is drastically smaller than urban areas( 80.9% ).

*Figure 4 - Driver Count Data (2019)*
![This is an image]
 
*Figure 7 - Percent of Total Drivers by City Types*
![This is an image]
 
### PyBer Rides Statistics
The following box plot  chart shows ride counts per city. As with the driver statistics, there seems to be correlation between driver counts and rides. We also see an outlier (Figure B). Urban areas are 68.4% of all PyBer rides!

*Figure 2 - Ride Count Data 2019*

![This is an image]
 
*Figure 6 - Percent of Total Rides by City Types*

![This is an image]
 
*Figure B – Urban Outlier*
Python function to retrieve additional details on the outlier. West Angela has the highest rider count. Meaning this urban town has the highest ride demand.

![This is an image] 

### PyBer Fares Statistics
When it comes to Pyber Fare we can see a similar rate regardless of the city. Although Rural areas may be a bit more, the average fares fall between $24 - $35 per ride. We can see Urban area make up most of the revenue (62.7%) for Pyber rides.

*Figure 3 - Fare Data per City  2019*

![This is an image]
 
*Figure 5 -  Percent of Total Fares by City Types*

![This is an image]
 

## Summary: 
Based on the results, we would recommendation the board of PyBer to  addressing driver disparities among the urban and rural areas. Due to the supply and demand (rides requested and available drivers) we can analyze if all rides are being fulfilled. Other possible questions to ask – 
•	What time of the day are most rides being requested?
•	How many active pyber drivers are available to fulfill rides?
•	Average distance of rides per city? Per driver?
