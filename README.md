# Make effective data visulization
## Summary

The dataset I used for this project is found on Kaggle, containing air quality information of main Chinese cities from 2010 to 2015. I used the data for Shanghai to explore the impact of differnet weather conditions to the air quality, which is represented by PM2.5.

## Design

Originally I have made line chart to show the seasonality, and scatter plot to reveal the bi-variable correlation, after receiving the comments, I added animation, and color encode to the line charts and scatter plot.

## Feedback to the original design
#### What do you notice in the visualization?

I see a line representing the PM 2.5 along year 2015 and it was starting from March that this index got stablize, which was less than 100. Again starting from Nov, the index got increased and surpassed 100. Is it possible to show more comparison across year and season?

I also see for the scatter plot, the horizontalaxis is PM 2.5 index and vertical axis is wind speed. I understand that the red color means that the PM 2.5 is bad and green means the air quality is good. My understanding was confirmed when hovering onto each of the data point.

#### What questions do you have about the data?

What's the granularity of the data used in this project?
What's the source of this dataset?

#### What do you think is the main takeaway from this visualization?

I hope if it is possible, to see a year by year comparison, and it is already good to have the yearly pattern.
If there any more correlation could be explored via the scatter plot?

#### Is there something you don’t understand in the graphic?
Nope...

## About the Data Set
The data set was originally found on Kaggle. There are two data sets are used for generating the charts in ShanghaiPM_final.html and ShanghaiPM_origin.html. 'PMShanghai_2015.csv' was used for the original html to scratch some ideas and also used for the scatter plot in the final html. 'PMShanghai_daily.csv' was used to generate the line chart.

## Resources
https://developer.mozilla.org/en-US/docs/Web/CSS {grasped CSS basics}\
https://developer.mozilla.org/en-US/docs/Web/HTML {grasped html basics}\
https://github.com/PMSI-AlignAlytics/dimple/wiki {where I went through the basic dimple functionality}\
https://www.health.ny.gov/environmental/indoors/air/pmq_a.htm {where I get some background knowledge about PM2.5}\
https://www.kaggle.com/ {where I found my dataset}\
https://github.com/vverde/Udacity-Data-Analyst-Nanodegree-P6 {where I found a sample project model}
