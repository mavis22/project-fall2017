# Write-up 
## The reason we took the approach
Our approach is based on the requirements of component 1. The first requirement is data cleaning, we used `pandas` and `numpy`. Pandas can help us to deal with dataset, while haversine can be used for calculating the distances between stations and Tohoku. Next requirement is data visualization. In this part, we used `matplotlib.pyplot`. The last requirement is intractive, we used `ipywidgets` for this part. We also used `haversine` and `math` for the data processing.
## Strengths of our approach
Most of approaches we used are for data processing: `haversine` is the easiest way for us to get the distance between stations and Tohoku, since we already got 'longitude' and 'latitude' for each stations. Basically `pandas` and `numpy` used together for data analysis. They can display a great dataframe to help us to track data. And we can keep the different data types in one dataframe. And `pandas` has a lot of powerful built-in functions, like groupby and so on. We applied `matplotlib.pyplot` on our visualization part, it will give us default plot stypes with built-in code. 
## Weaknesses of our approach
  * We missed the map background. With a map background, it will be more clear to see where the stations are.
  * It will be very good for us to add a play button. It will give better user experience.
## Things we wished we had been able to do
  * Data processing: Reorder the data by distance.
  * Data visualization: Map, spectrogram and line plot.
  * Intractive: Time slider and click event.
## Group attribute:
  * Code:
  * Data processing:
  * Debug:
  * Write up:
