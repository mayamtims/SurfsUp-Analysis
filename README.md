# SurfsUp-Analysis

## Overview
The purpose of this analysis was to compare June and December temperatures on Oahu, Hawaii to determine if the surf shop will attract customers year-round. Using Python, Pandas and SQLAlchemy, a dataset was retrieved from the hawaii.sqlite database. The temperature data from June and December were then queried and transferred into Pandas Dataframes, and the summary statistics (count, mean, standard deviation, minimum, 1st quartile, 3rd quartile and maximum) of each were obtained. 

## Results
There are three major points we can takeaway from the comparison:
1. The average temperature in June (74.9 degrees) and the average temperature in December (71.0 degrees) differ only by a few degrees.
2. The standard deviation for the month of December (3.4) is higher than the standard deviation for the month of June (2.6), meaning that the temperature varies more day to day in December. 
3. There are more points of data for the month of June (1700) than there are for the month of December (1517). 

Summary statistics tables for June (left) and December (right):

![june_temps](https://github.com/mayamtims/SurfsUp-Analysis/blob/main/Resources/june_temps.png)
![dec_temps](https://github.com/mayamtims/SurfsUp-Analysis/blob/main/Resources/dec_temps.png)


## Summary
This analysis indicates that temperatures are warm enough for the surf shop could stay open year round. Even in December the temperatures are still good for surfing, and warm enough for ice cream. In order to get a better idea if it is viable for the surf shop to remain open all year long, the same analysis should be run for the amount precipitation in June and December. In addition, it would be a good idea to run these temperature and preceipitation analysis for the last 10 or 15 years to determine if the weather patterns are consistent. 