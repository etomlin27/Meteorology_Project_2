# Meteorology_Project_2
Project 2 For BME 450 Winter 2020

Code URL:
Raw Code URL:
README URL:

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

These times can then be compared between the two sites to determine cross corrilation and see how weather events my move and expand in the region.


![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure3.png)

*Figure 1a: Oregon Slope Base Shallow Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure4.png)

*Figure 1b: Oregon Slope Base Shallow Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure7.png)

*Figure 2a: Oregon Offshore Cabled Shallow Profiler Mooring SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure8.png)

*Figure 2b: Oregon Offshore Cabled Shallow Profiler Mooring SSP for Winter.*

For the remaining instruments when comparing the frequency of dives in a 24 hour period, it was not consistant for the shallow or deep insruments to perform more dives. The Oregon Offshore Cabled Deep Profiler Mooring performed many more dives than its shallow counterpart as seen in figures 3a-b but the Axial Base Shallow Profiler performed more dives than its deep counterpart as seen in figures 4a-b and 5a-b. Due to the limited data and inconsistancy of the dates, the average speed of sound profile can not be compated between instruments with any validity. Examining the data purely from a seasonal perspective and assuming the geographic proximity is negligible, it can be seen in the comparisons in figures 3-7 a-b that the summer speed of suind profle shifts the curve up, documenting a lower speed of sound nearer to the surface. This is consistant with expectations that in warmer weather, the extra sunlight results in increased temperature at the surface and increased runoff in costal areas. Both these factors lower the water density in proximity to the surface which in turn lowers the speed of sound.

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure1.png)

*Figure 3a: Oregon Shelf Surface Piercing Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure2.png)

*Figure 3b: Oregon Shelf Surface Piercing Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure5.png)

*Figure 4a: Oregon Offshore Cabled Deep Profiler Mooring SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure6.png)

*Figure 4b: Oregon Offshore Cabled Deep Profiler Mooring SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure9.png)

*Figure 5a: Oregon Slope Base Deep Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure10.png)

*Figure 5b: Oregon Slope Base Deep Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure11.png)

*Figure 6a: Axial Base Shallow Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure12.png)

*Figure 6b: Axial Base Shallow Profiler SSP for Winter.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure13.png)

*Figure 7a: Axial Base Deep Profiler SSP for Summer.*

![alt text](https://github.com/etomlin27/CTD_Project1/blob/master/Figure14.png)

*Figure 7b: Axial Base Deep Profiler SSP for Winter.*

Regardless of the season, the maximum value for the speed of sound occured at the lowest depth for the deep sensors and the surface depth for the shallow sensors. This is likely due to the minimum value occuring between the two sensors and thus each sensor only displayes the upper or lower end of the curve. 

The effects of day vs. night could not be analyzed do to time constraints restricting the conversion of the instrument time to local time. The expected effect is that in the daytime as temperatures at the surface are higher, the speed of sound profile will shift up slightly. This effect is expected to be much less in magnitude than the similer influence of the differing season, but follow the same reasoning. The increased temperature lowers the density near the surface, but has little effect in the depths and thus raises the depth with the minimum speed of sound.


## Conclusion:

Temperature changes in the ocean, usually as a result of solar radiation measured at different times of day and different seasons in the year, has a dominant effect on the speed of sound through the water. As the temperature of the ocean in increased, especially near the surface, the speed of sound profile shifts up. This is further illistrated by examining the formula for calculating the speed of sound in water as seen in equation (1). It can then be extrapolated that further effects on ocean temperature from climate change and pollution can have a dramatic affect on the acoustic properties of the water. This in turn, will likely have a severe adverse affect on any marine life that depends on the accoustic properties for their wellbeing and survival.

## References:

https://ooinet.oceanobservatories.org/
