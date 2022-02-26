# Surfs Up Analysis
## Overview
An entreprenuer has developed a business proposal for a surf and ice cream shop located on the island of Oahu. Before committing funds, investors request an analysis of weather data to determine the year-round sustainability of such a business. Multi-year temperature data for Oahu was queried to obtain records specific to the months of June and December and analyzed using SQLite and Python. Resulting summary statistics are described and assessed in the subsequent analysis. 
## Analysis Results
### June Temperature Data
- There were 1700 temperature data points for June
- Data coverred a temporal range of 2010 to 2017
- Summary statistics for temperature are displayed below.
  ![June summary statistics for temperature](https://github.com/InRegards2Pluto/surfs_up/blob/fae7841ba3052719b9b388dd993e28dce26592cd/Resources/sum_stats_temp_June.png)
### December Temperature Data
- There were 1517 temperature data points for December
- Data covered a temporal range of 2010 to 2016
- Summary statistics for temperature are displayed below.
  ![December summary statistics for temperature](https://github.com/InRegards2Pluto/surfs_up/blob/fae7841ba3052719b9b388dd993e28dce26592cd/Resources/sum_stats_temp_June.png)
### Key Differences
1) There are 183 more data points for June than for December.
2) The minimum temperature in June is 64 degrees Farenheit whereas the minimum temperature for December is 56 degress Farenheit.
3) The average temperature is slightly higher in June compared to December (74.9 and 71.0, respectively).
4) The lower quartile for June is higher than the lower quartile for December (73 and 69, respectively).  
## Summary
- The months of June and December are similar in Oahu on the basis of temperature data alone. While 25, 50, and 75 percentiles are slightly upshifted in June compared to December, quartile statistics suggest that December is still fairly warm (and very ice cream worthy). 
- However, it's worth noting that the month of June has an additional year of data compared to December. Further, minimum temperatures for June and December are 64 and 56, respectively. While 56 degrees is still ice cream weather for a Michigan resident, Hawaiian residents might consider that kind of weather to be chilly and not the kind of weather for ice cream.
- While this analysis features summary statistics on bulk data, it does not sufficiently capture shifting annual temperature trends. Even if only 25% of the temperature values are below 69 degrees Farenheit in December, are these data points distributed evenly across years? Or are those data points more focused in recent years? Also, half of the business is a surf shop. Are water temperatures in December as warm as air temperatures? Or is the water too cold for surfing? Is there more precipitation in December that might deter customers from patronizing the business? These and other questions should be addressed prior to investment commitments.
### Additional Queries
- To address remaining questions on weather data, the following queries could be considered:
  1) Bin temperature data for June and December according to the year data was collected.
  2) Compare precipitation data for June and December to see if rainier weather might limit customers to a surf and ice cream shop.



## Resources
- Data Sources:
  - [hawaii.sqlite](https://github.com/InRegards2Pluto/surfs_up/blob/fae7841ba3052719b9b388dd993e28dce26592cd/hawaii.sqlite)
  - [SurfsUp_Challenge.ipynb](https://github.com/InRegards2Pluto/surfs_up/blob/fae7841ba3052719b9b388dd993e28dce26592cd/SurfsUp_Challenge.ipynb)
- Software:
  - Jupyter Notebook
