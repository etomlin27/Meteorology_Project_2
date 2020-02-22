# Meteorology_Project_2
Project 2 For BME 450 Winter 2020

Code URL: https://github.com/etomlin27/Meteorology_Project_2/blob/master/Tomlin_Project2_Meteo.ipynb
README URL: https://github.com/etomlin27/Meteorology_Project_2/blob/master/README.md

## Problem Statement:

To understand how weather changes as it moves inland from the ocean it is necessary to have a means of measuring and comparing different meteorological parameters. For the purpose of this study, wind velocity and rain rates will be compared across one year and between 2 different ocean observitories: the Costal Endurance Oregon Surface Shelf Monitoring station and the Costal Endurance Oregon Offshore Surface Mooring. Both of these observitories have bulk meteorological sensing packages that can measure the parameters. The data can then be aggrigated and analyzed using python.

## Backround/ Solution/ Results:

Graphical analysis of when the rain and wind crosses accepted thresholds (0.5 mm/hr and 5 m/sec respectively) will illistrate when each site is rainy or windy. Figures 1a-c and 2a-c show the weather profiles across 2019 for the two observitories.

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Rain_and_Wind_OS.png)

*Figure 1a: Rain and Wind Rates for Oregon Offshore Surface Mooring.*

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Weather_Stripes_OS.png)

*Figure 1b: Weather profile across 2019 for Oregon Offshore Surface Mooring.*

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Combined_OS.png)

*Figure 1c: Combined Profile for Oregon Offshore Surface Mooring.*

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Rain_and_Wind_SS.png)

*Figure 2a: Rain and Wind Rates for Oregon Surface Shelf Monitoring Station.*

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Weather_Stripes_SS.png)

*Figure 2b: Weather profile across 2019 Oregon Surface Shelf Monitoring Station.*

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Combined_SS.png)

*Figure 2c: Combined Profile for Oregon Surface Shelf Monitoring Station.*

These times can then be compared between the two sites to determine cross corrilation and see how weather events my move and expand in the region. Comparing the Wind Speeds between the sites and cross corrilating, there is a strong corrilation. This is as expected as the wind is a large scale event and it would be unusual for there to be a high number of data points where one site is windy and the other isn't. Based upon the overlayed graphs as seen in figure 3, the offshore wind is higher than the shelf with a slight lag. This also follows expectaions as the wind has little resistance over the open ocean, but as it approaches shore thermal resistance become more prevelant. The Maximum correlation occurs at lag 1, indicating near simultainious events based upon the time period examined. As the data is recorded roughly every 8 hours, this indicates that the weather travels between the two sites in 8 hours or less. The max correlation value for the wind is 0.715 and indicates a decently strong correltation.

![alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Wind_Correlation.png)

*Figure 3: Wind Correlation Data.*

Conducting the same analysis on the rain, a similer pattern emerges. As seen in figure 4, the rain's maximum correlation also occurs at lag 1 with a maximum value of 0.634. This is a moderatly strong correlation, but less so than the wind. This observation suggests that the rain does not behave quite the same way as the wind, and may dissipate between sites. Overall, the rain is still corellated and, interestingly, opposite of the wind in that the higher rain rates occur inland. Once again this is consistant with expectations as rain is usually formed as a result of atmospheric pressure changes that are more prevelant as a result of elevation and thermal changes from landmasses.

[alt text](https://github.com/etomlin27/Meteorology_Project_2/blob/master/Rain_Correlation.png)

*Figure 4: Wind Correlation Data.*

Regardless of the season, the maximum value for the speed of sound occured at the lowest depth for the deep sensors and the surface depth for the shallow sensors. This is likely due to the minimum value occuring between the two sensors and thus each sensor only displayes the upper or lower end of the curve. 

The effects of day vs. night could not be analyzed do to time constraints restricting the conversion of the instrument time to local time. The expected effect is that in the daytime as temperatures at the surface are higher, the speed of sound profile will shift up slightly. This effect is expected to be much less in magnitude than the similer influence of the differing season, but follow the same reasoning. The increased temperature lowers the density near the surface, but has little effect in the depths and thus raises the depth with the minimum speed of sound.


## Conclusion:

Temperature changes in the ocean, usually as a result of solar radiation measured at different times of day and different seasons in the year, has a dominant effect on the speed of sound through the water. As the temperature of the ocean in increased, especially near the surface, the speed of sound profile shifts up. This is further illistrated by examining the formula for calculating the speed of sound in water as seen in equation (1). It can then be extrapolated that further effects on ocean temperature from climate change and pollution can have a dramatic affect on the acoustic properties of the water. This in turn, will likely have a severe adverse affect on any marine life that depends on the accoustic properties for their wellbeing and survival.

## References:

https://ooinet.oceanobservatories.org/
https://www.noaa.gov/

https://stackoverflow.com/
