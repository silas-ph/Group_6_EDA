# Project 1 Group 6 Exploratory Data Analysis (EDA)
## Changes in Air Traffic Patterns During Covid-19 and After
> Team Members:
> Ava Lee,
> Jed Murphy, 
> Silas Philips, 
> Christoph Guenther
  
### Project Overview
As the Covid-19 virus spread globally in early 2020, the routines of daily life changed drastically for many people around the world. As the U.S. went into lockdown to slow the spread of the virus, travel, business as well as leisure, changed drastically. It is well known that the U.S. domestic airline industry, among many others, experienced an unprecedented crisis during that time[^1].

Using United States Department of Transportation commercial air travel data, we compare U.S. air passenger traffic patterns before, during, and after the Covid-19 pandemic. The purpose is to obtain a more detailed and quantitative understanding of how air travel patterns look different during the pandemic from before and after. We also aim to understand how air traffic patterns might still be different after Covid-19 as compared to before Covid-19.

### Summary of Findings and Conclusions
Our analysis shows that air traffic patterns changed significantly during Covid-19. At its lowest points passenger volume was down by 95.5% as compared to its average before Covid-19, the number of flights decreased by 75.5% from its pre-pandemic average, and airfare decreased by 32.8%.

Our analysis further shows that the minimum in passenger volume and the number of flights was reached in the first few months of the Covid-19 pandemic. It also revealed that there is a lag between when passenger volume reached its minimum and when the number of flights was at its lowest point. At the same time, the number of cancelled flights increased significantly in the first months of Covid-19.

We concluded that in the first few months of the pandemic, the airline industry reacted by cancelling flights before they reduced the number of flights.

Our analysis further revealed that airfares reached their minimum about three months after the passenger volume reached its minimum and that the decline in airfares was much less severe than the decline in passenger volume or the decline in the number of flights. Further investigation is needed to better understand this pattern.

Recovering from the pandemic, we saw that passenger volume had recovered to its average before Covid-19 by July of 2021. However, other metrics, notably the number of flights and the airfare, were still depressed as compared to their pre-pandemic averages. In fact, the median airfare has still not reached the same level it had before Covid-19.

We also saw that the average arrival delay after the pandemic has increased compared to before Covid-19. This was accompanied by an increase in the number of passengers per flight after Covid-19. This makes sense since passenger volume is close to its pre-pandemic levels, but the number of flights is still smaller than pre-pandemic levels, which should lead to an increase in the number of passengers per flight.

The increased number of passengers per flight might also explain the observed increase in delay since more passengers per airplane might cause delays because it might take more time to process these passengers.
In addition, the airlines might have reduced staff during the pandemic and are still short on personnel. Therefore, fewer personnel must process a similar number of passengers, leading to delays. Further investigation is needed to confirm the correlations supporting this hypothesis.

Finally, we observed that some of the patterns and metrics have still not recovered to their patterns and levels before Covid-19. As mentioned above, the median airfare is still lower, arrival delays are higher, the number of passengers per flight is higher, and the correlation between passenger volume and airfare is still very similar to that during Covid-19. Further investigation is needed to determine whether these differences will prevail.

### Further Information
Further information can be found in our report entitled "CHANGES IN AIR TRAFFIC PATTERNS DURING COVID-19 AND AFTER". It can be found at 

### Layout of this GitHub Repository
We wrote a Jupyter Notebook script called `p1_flight_data_analysis.ipynb` to perform data processing, data exploration, and data visualization. It can be found in the root folder of this repository. The root folder also contains this README.md file

All other files can be found in the following three subfolders:
 * `/Resources`: It contains all of the data files used in this project.
 * `/Plots`: It contains all the plots used in the report and/or the presentation.
 * `/Docs`: It contains our report named "Group 6 Report.pdf" and a file with the presentation slides called "Group 6 Presentation.pdf". This folder also contains the original Word documents for the report and the presentation.

### Special Instruction
1. The `/Resources` file has a size of about 20GB. So, make sure there is enough hard disk  space available on your computer. Depending on your bandwidth, it might take some time to download this folder as well.
2. The `p1_flight_data_analysis.ipynb` requires close to 6GB of RAM to execute.
3. The correlation matrix heatmap might not display its values properly unless you use `Matplotlib` library version 3.7.3.

[^1]: Leslie Josephs (August 16 2020). *A flood of job losses looms as airline industry struggles in pandemic*, CNBC website, https://www.cnbc.com/2020/08/16/a-flood-of-job-losses-looms-as-airlines-industry-struggle-in-coronavirus-pandemic.html as accessed on 4/22/2024.
