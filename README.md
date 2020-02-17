# PyBer_Analysis

### Background
We were asked to create asummary table of key metrics of the ride-sharing data by city type (Urban, Suburban and Rural, and a multiple-line graph that shows the average fare for each week by each city type.

### Objectives
Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
Use Pandas methods and attributes on a DataFrame or Series.
Create a new DataFrame from multiple groupby() Series.
Format columns of a DataFrame.
Create a multiple-line graph.
Annotate and apply styling to the chart.

### Materals 
Python 3.7.4 <br /> 
Anaconda Navigator 1.9.7 <br /> 
Jupyter Notebook 6.0.1 <br /> 
city_data.csv <br /> 
ride_data.csv <br /> 

### Summary
Through my analysis of the ridesharing data using Python and Matplotlib I have uncovered that there are significant differences in the data based on location. According to the dataframe, Rural cities have the lowest total rides, lowest total drivers and lowest total fares. There is significant evidence to show that this low activity leads rural cities to have the highest average fare per ride and the highest average fare per driver. On the other end of the spectrum, urban cities have the highest total rides, highest total drivers and highest total fares. There is significant evidence to show that this high activity leads urban cities to have the lowest average fare per ride and the lowest average fare per drive. With suburban cities, we can see that their data is in the middle of the urban and rural cities. 

The multi-line graph supports the numbers in the summary data frame. Urban cities have the highest total fares folowed by suburban and then rural cities. We can see that as the year progresses, each city type stays relatively consistent with minor peaks and troughs. There may be an inverse correlation between the total fares in the urban cities and the total fares in the suburban and rural cities. The graph shows that when total fares in rural and suburban cities are higher, total fares in urban cities are lower and vice versa. A potential explaination for this could be that riders from the suburban and rural cities are riding to and from the urban cities.  
