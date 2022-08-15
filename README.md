# Surfs_Up-Analysis

## Overview


### Purpose

* Client has requested information about temperature trends in Hawaii as part of his research into opening a surf and ice cream shop.  Specifically, he wants temperature data for the months of June and December on the island of Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

### Data Description

* The data provided is a SQL Lite database containing 2 tables, one that holds 7 1/2 years of weather indicators in Oahu (temperature and precipitation), and another that provides the ID, latitude, longitude and elevation of the weather monitoring station that provided the readings. 


## Deliverables

### 1.  June and December temperature analyses:   
 * June temperature summary statistics table
 * ![image](https://user-images.githubusercontent.com/107505166/184559275-c416444e-1c4a-46fc-8bcc-fea442473505.png)

    
 * December temperature summary statistics table
 * ![image](https://user-images.githubusercontent.com/107505166/184559933-00bba892-d5b5-4185-939f-dc471b899a06.png)

## Results  
     
 * The temperature differences in June and December are relatively minor.  Although the minimum temperature in December is lower than that in June, and the maximum temperature in June is higher than that in December, the average temperature is only a 4-degree difference and is very temperate.
    
 * There are roughly 12% more temperature readings in the dataset for June versus December which could affect the data slightly.
    
 * Considering temperature as a major factor, the Oahu location will boast a comfortable temperature in both June and December although ice cream sales may be slightly lower in December due to the slightly lower average temperature and lower max and min temperatures.
 
 ### Summary and Recommendations:
 * The data set  provided for analysis includes temperature readings throughout the island of Oahu which include sea-level to higher elevations.   It's recommended to    exclude from the analysis the readings from the high-elevation stations by filtering these out.
 
 * Including rainfall readings in the analysis would be helpful, again, excluding data from the higher-elevation weather stations.   Without filtering the data on the weather stations at sea-level and near the location of the proposed surf shop, it's difficult to see how preciptation may affect surf shop and ice cream business throughout the year.   Currently, without any filtering on the location or the elevation of the weather station, we can see that there is 57% more inches of precipitation in December than in June.
  
     June Precipitation (inches)        0.13636
     December Precipitation (inches)    0.216819

* Nothing in the temperature analysis points to any temperature-related barrier to operating the surf shop/ice-cream shop in Oahu year-round.
   
