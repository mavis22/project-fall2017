# Write-up 
## The reason we took the approach
We used dot visualization on the map to represent the location of the earthquake detectors which distribute in the USA. The whole visualization will show use the infomation we got from the detectors 2011 Tohoku earthquake in Japan on March 11, 2011. As we mentionded before each dot on the map means a detetor location. For each point, it will change the color based on the earthquake strength which got by the detectors when we change the time slider. On the bottom right side of the visualization, it will show a line plot to represent the earthquake strength for the period by the selected detector on the left side map. While on the top right, the soectrogram willl represent the strength records by all the detectors and whole time period with the cross line to represent current detector and time.
## Strengths of our approach
This will give us a clear view of Tohoku earthquake, include of how long it last, when the highest strength is, how long the interval is between the earthquake and how the earthquake wave transmit. Since we made the visualization as the interactive. It will give the users better experience and chance to review the time or detector they are interested. 

We have several versions of code.
### For Component_1_Version_1:
Initially, we implement all required functions using matplotlib.pyplot. 

### For Component_1_Version_2:
In order to solve the drawback mentioned below, we using the mix of matplotlib.pyplot and bqpot packages and change the selection of detector by using clicking. 

### Extra:
We finished the transformation of audio for wave of detectors.

## Weaknesses of our approach
We have several versions of code. Generally, our weaknessess are:
  * We missed the map background. With a map background, it will be more clear to see where the stations are if we come with a backgroud.
  * It will be very good for us to add a play button, which can change the time slider automatically with variable steps. It will give better user experience.
  * A sound generater may help people to get better understand about how the strength was in the earthquake period.
  * The value selected on the time slider is not shown as the natural format of time. It would provide better user experience if we could provide a time slider with natural time format shown.
Specifically,
### For Component_1_Version_1:
We implemented all required functions using matplotlib.pyplot. The drawback is that detectors are selected using dropdown box. Since there are over 400 detectors, it is a fairly long dropdown and not easy for use.

### For Component_1_Version_2:
We successfully implement the click event handling, but a new problem is that, everytime we click a new detector, a new spectrogram with the horizontal line indicates the selected detector would be generated. Luckily, when we change the time slider, the vertical line which indicates the time point selected would be changed directly on the original spectrogram.

## Things we wished we had been able to do
  * A movie shows the change of magnitude every detector felt.
  * Data visualization: US map as background of scatter plot
  * Natural shown time slider.

## Group attribute:
  * Code:Mingwei Gao, Liri Fang
  * Data processing:Zixin Ouyang
  * Debug: Liri Fang, Jianshan Yang 
  * Write up: Jianshan Yang, Mingwei Gao
