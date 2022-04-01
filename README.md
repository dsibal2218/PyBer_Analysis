# PyBer_Analysis
**Overview**: For this challenge, we were given 2 data sets for PyBer, a ride-sharing company. The first one is the city dataset that has the city name, number of drivers per city and the type of city (ie urban, suburban and rural). The second dataset has the ride data. It contains the city, date of the ride, fare and unique ride IDs. We are to create a summary DataFrame of the ride sharing data by city type using Python and Pandas. Additionally, we are to create multiple-line graph that shows the total weekly fares for each city type using Matplotlib. Finally, we are to write a report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Requirements and Details of the Analysis
1. Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type. 

<img width="634" alt="Screen Shot 2022-04-01 at 11 52 48 AM" src="https://user-images.githubusercontent.com/98235755/161298791-c4145a60-b960-4152-9fe6-a588080681b1.png">


2. Calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.


<img width="639" alt="Screen Shot 2022-04-01 at 11 29 51 AM" src="https://user-images.githubusercontent.com/98235755/161294872-64b334b6-0d39-4c61-80cd-f310d810ac3f.png">


<img width="646" alt="Screen Shot 2022-04-01 at 2 15 04 PM" src="https://user-images.githubusercontent.com/98235755/161323299-a6a755e3-4475-484a-a72e-40cacf0dd35c.png">

3. Using Pandas' pivot() and resample() functions, get the total fares for each week (for January 2019-April 2019) by city type.

<img width="642" alt="Screen Shot 2022-04-01 at 11 32 48 AM" src="https://user-images.githubusercontent.com/98235755/161295413-d5586bf0-f5f3-4bee-a742-5fb834484686.png">


4. Create a multiple-line graph of the resampled dataframe using object-oriented interface method, df.plot() method and Matplotlib's "fivethirtyeight" graph style code. Annotate the y-axis label and the title, the use the appropriate code to save the graph figure in a "analysis" folder.

<img width="653" alt="Screen Shot 2022-04-01 at 11 33 33 AM" src="https://user-images.githubusercontent.com/98235755/161295543-bebc9fbe-40bb-4b83-9221-6e0a04f4f937.png">

## Results of the Analysis
1. Urban city type had the highest total rides and drivers with 1,625 and 2405, respectively. Thus, earning the highest total fare amount among city types. However, it has the lowest average fare per driver and per ride with $24.53 and $16.57, respectively.

2. Rural city had the highest average fare per ride and per driver with $34.62 and $55.48, respectively.

3. Across three city types, the weekly average fare spiked up sometime during the last week of February.

**Summary/Recommendations**
1. Since urban had the highest total fare and rides but lowest average fare/ride and fare/driver, I would recommend performing additional analyses around staffing level to look into whether or not we have more drivers than demand. I would also recommend looking at city-level data. Typically in the urban area, driving distances are shorter, hence the lower average fare per ride so we might not actually need 2000+ drivers. If so, think strategically if there is a value in limiting the number of drivers per city or redistributing to other parts of the city.

2. For rural city, I would recommend performing analyses to answer questions like do we need more drivers in the rural area? how long does it take it for a ride request to be fullfilled from the time the customer requested for a ride (ie the longer time it takes for pickup, the more it may indicate that we need more drivers). If so, do we also need to market the service more?

3. Given there seems to be some seasonality around Feb, do we want to look into more staffing at that time? Should we look at how many requests we didnt fullfil or cancelled to see if we wait time was too long and if we really need to staff a bit more.
