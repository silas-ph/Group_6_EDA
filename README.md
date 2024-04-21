# Group_6_EDA
Group 6 Flight Data EDA project
AI Boot Camp Project 
## The Turbulent Journey: Possible Effects of the COVID-19 Pandemic on U.S. Domestic Air Travel
> Team Members:
> Jed Murphy, 
> Silas Philips, 
> Christoph Guenther, 
> Ava Lee

  
### Project Overview
Purpose:
Using United States Department of Transporation commercial air travel data, we compare U.S. air passenger traffic patterns before, during, and after the Covid-19 pandemic. The purpose is to obtain a more detailed and quantitative understanding of how air travel patterns look different during the pandemic from before and after. We also hint at how air traffic patterns might still be different post-Covid-19 as compared to pre-Covid-19.

### Background
As the Covid-19 virus spread globally in early 2020, the routines of daily life changed drastically for many people around the world. As the U.S. went into lockdown to slow the spread of the virus, travel, business as well as leisure travel, changed drastically. It is well known that the U.S. domestic airline industry, among many others, experienced an unprecedented crisis during that time.


### Goal
Our goal is to illustrate and quantify some of the changes in commercial U.S. air passenger traffic before, during, and after the Covid-19 pandemic.

### Questions to be addressed
 * How did domestic U.S. air passenger traffic change during Covid-19?  
   To answer this question we analyze the following metrics:
   * Air passenger volume,
   * Number of flights,
   * Passengers per flight,
   * Number of canceled flights,
   * Flight cancellation percentage,
   * Average air fare.
 * How long did it take for passenger volume to normalize to pre-pandemic levels after Covid-19?
 * How did the average airfare change during Covid-19?
   * If it changed, when did it change as compared to when passenger volume changed?
   * If it changed when did it normalize as compared to when passenger volume normalized?
 * Can we discern any changes between air passenger traffic before and after Covid-19?

### Overview of data collection
Data Sources: 
### $${\color{orange}Bureau of Transportation Statistics (BTS):}$$
Provides extensive data on US flights, including on-time performance, delays, cancellations, and more.   [BTS](https://www.bts.gov/topics/airlines-airports-and-aviation)

### $${\color{orange}Aviation Edge:}$$ 
Offers a suite of APIs providing access to various aviation-related data, including flight schedules, tracking, airport, and aircraft data. [AviationEdge](https://aviation-edge.com/)

### $${\color{orange}Aviationstack:}$$
Provides a powerful flight data API offering real-time and historical flight information, including tracking, status, routes, and airline details. [Aviationstack](https://aviationstack.com/)

### $${\color{orange}FAA:}$$
Offers a comprehensive dataset of airline routes, airports, and schedules freely available for download, useful for researchers and developers. [FAA](https://www.faa.gov/)

### $${\color{orange}Transportation.gov:}$$ 
Offers multiple data sets.  [Transportation](https://www.transportation.gov/)

### Cleanup and exploration approach 

	- Clean up missing values, outliers, and duplicate data.
	- Normalize or scale numerical features for diagrams.
	- Calculate summary statistics for numerical features.
	- Explore the distribution of numerical features using histograms, box plots, or violin plots.
	- Examine the frequency distribution of categorical features using bar plots or count plots.
	- Correlate analysis to detect patterns within time series data.
	- Create geographical visualizations using maps to analyze spatial data.
	- Use advanced plotting libraries like Plotly or Seaborn for more customized visualizations.

### Result/Conclusion 

![Passenger Number by Year](./Passenger_Number.png)

![Passenger Number by Year over Year](./year_over_year.png)

![Cancellation Per Year](./cancellation.png)
![Average Passengers per Flight Across Sates and Time](./per_flight.png)

### Summary
<<<<<<< HEAD
Our data analysis shows that airline passengers and flights reached record lows at the beginning of the pandemic and that it took between a year and a quarter to a year and a half from that low for passenger and flight numbers to reach pre-pandemic levels. We will also analyze changes in the number of canceled flights and the relationship between average delay and the number of passengers. Finally, we will provide insights into how air passenger traffic patterns might have changed post-pandemic.
=======

>>>>>>> 7728ad3835aac063ac98cc8de489641e453b3caa

### Problem Encountered

	* Storage issue with GitHub
	  	- GitHub has a 1G storage limitation.  The amount of data we were working with was
    	  beyond that.  So we believed that the data was corrupted, leading us to spend 
	          hours finding a solution
	* Size of dataframes for a personal machine
	* Datasets specifics are not available
	  	- Airfare information is only available by quarter
          	- All additional information is available by month
          	- To get additional information, it would cost more 

### Future Considerations
* How were these industry adjustments reflected in customer satisfaction
* Determine if areas with lighter COVID restrictions recover faster than the areas with heavier restrictions
* How this data would reflect internationally






























