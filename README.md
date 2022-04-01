# PyBer_Analysis
**Overview**: For this challenge, we were given 2 data sets for PyBer, a ride-sharing company. The first one is the city dataset that has the city name, number of drivers per city and the type of city (ie urban, suburban and rural). The second dataset has the ride data. It contains the city, date of the ride, fare and unique ride IDs. We are to create a summary DataFrame of the ride sharing data by city type using Python and Pandas. Additionally, we are to create multiple-line graph that shows the total weekly fares for each city type using Matplotlib. Finally, we are to write a report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Requirements and Details of the Analysis
1. Using the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, get the total number of rides, total number of drivers, and the total fares for each city type. 

<img width="660" alt="Screen Shot 2022-04-01 at 11 26 58 AM" src="https://user-images.githubusercontent.com/98235755/161294495-3ba6e410-4ab0-40cf-b114-b705fe367e40.png">

2. Calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.

<img width="639" alt="Screen Shot 2022-04-01 at 11 29 51 AM" src="https://user-images.githubusercontent.com/98235755/161294872-64b334b6-0d39-4c61-80cd-f310d810ac3f.png">

<img width="637" alt="Screen Shot 2022-04-01 at 11 30 37 AM" src="https://user-images.githubusercontent.com/98235755/161295020-f89e2396-b06f-4463-b120-bba60ab3d37e.png">


3. Using Pandas' pivot() and resample() functions, get the total fares for each week (for January 2019-April 2019) by city type.

<img width="642" alt="Screen Shot 2022-04-01 at 11 32 48 AM" src="https://user-images.githubusercontent.com/98235755/161295413-d5586bf0-f5f3-4bee-a742-5fb834484686.png">


4. Create a multiple-line graph of the resampled dataframe using object-oriented interface method, df.plot() method and Matplotlib's "fivethirtyeight" graph style code. Annotate the y-axis label and the title, the use the appropriate code to save the graph figure in a "analysis" folder.

<img width="653" alt="Screen Shot 2022-04-01 at 11 33 33 AM" src="https://user-images.githubusercontent.com/98235755/161295543-bebc9fbe-40bb-4b83-9221-6e0a04f4f937.png">

## Results of the Analysis
1. Urban city type had the highest total rides and drivers with 1,625 and 59,602

**Summary**
