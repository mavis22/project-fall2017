# Write-up 

## Our approach and the reason we took the approach
We used color maps to show the distribution of UFO total sightings and duration seconds from 1910 to 2014 in U.S. Different colors represent different numbers. Red represents relative large numbers, blue presents relative small numbers, and grey represents the middle. If there are only 0 and 1 in a particular year, black presents 0 while grey represents 1. The time slider is used to select a particular year. There are two drop down menus in the visualization. One is used to select whether to show the total sightings or duration seconds, and the other is used to select whether to show plots before normalization or after normalization. When we click on a state in the map, the plots on the right side shows the line plot of total sightings and duration seconds of that state from 1910 to 2014. When click on the background, the line plot will disappear. The total sightings and duration seconds of UFO reporting might be related to population in each state, so we use historical population of each state in U.S. for normalization. The dataset can be found at https://en.m.wikipedia.org/wiki/List_of_U.S._states_by_historical_population . 

## strengths of our approach
Since the numbers of total sightings and duration seconds are very different, we can get intuitive impression from different colors in color maps. From the line plot, we can directly see the trend, maximum, minimum, modes and which year has the largest increase or decrease. We can explore more information based on the visualization. We used a separate drop down menu of "normalized", which made the comparison before and after normalization straight-forward.

## Weaknesses of our approach
The weakness of our visualization is that we only consider one field for normalization since it is hard to find the data of other factors for more than 100 years.

## Things we wished we had been able to do
We wish we had been able to dig deeper into the data and provide more information about UFO reporting. For example, we could have investigated which state had the most or least UFO reporting, and at which time period the sightings were reported most often.

## Group attribute:
Jianshan Yang cleaned the UFO dataset, and modified the codes provided by professor to create visualization. Liri Fang and Mingwei Gao have edited the visualization further. Liri Fang mainly worked on the colored map, and Mingwei Gao mainly worked on line plot and click event handling. Zixin Ouyang worked on the additional data search, normalization and final write-up of this component. 