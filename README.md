
UBER TRAFFIC ANALYSIS
(A data visualization project on Tableau)
About the dataset
The dataset of Uber Traffic (Bengaluru) has been picked up from Kaggle to analyze and visualize the various aspects of vehicular traffic in the city of Bengaluru from  January 2016 to March 2018. The various features of the data are:
Date, Origin, Destination, 
Daily Mean Travel Time and Range – Upper and Lower Bound Travel Time,
AM Mean Travel Time and Range – Upper and Lower Bound Travel Time,
PM Mean Travel Time and Range – Upper and Lower Bound Travel Time,
Midday Mean Travel Time and Range – Upper and Lower Bound Travel Time,
Evening Mean Travel Time and Range – Upper and Lower Bound Travel Time,
Early Morning Mean Travel Time and Range – Upper and Lower Bound Travel Time,

Why this dataset
A common yet significant problem is that the modern Indian cities are witnessing a great rise in vehicular traffic along with the increase in cabs. It is important to study and analyze how traffic moves and changes during different times in a day and what is the role of cabs and car pooling in the traffic scenario. This dataset can be used to analyze and create awareness about carpooling as well as the pollution level control due to this. 
We all know that in the metro cities, cabs have become an indispensable part of life, so exploring and visualizing this dataset can help us dive deeper into the social and economical aspect of the problem and to plan measures accordingly.

Our goals 

We wish to find the answers to the following questions using the amazing data visualization tool – Tableau:
Which day of the week experiences maximum traffic, what could be the reasons
Which month of the year experiences maximum traffic, what could be the possible reasons
Which time of the day experiences maximum traffic, what could be the possible reasons
Average time an Uber spends on road daily
No. of taxis on different days segregated by different time intervals to figure out the busier days and busier times.
Correlation between different time durations.

Visualization and Understanding the Trends
Comparison of Travel Time during Different Months:
There is not much variation seen in the daily travel time of the taxis over different months. Though we can see that the cabs seem to take more time to travel the same distance during the months of January and December. Also, the we can see that there is a lot of traffic during the Night time. Night time seems to be the busiest for Uber cabs. 
After a thinking and discussion process, we could infer that this could be because of the office timings in the evening, or might be because of the parties and night clubs etc.

Travel Time during Different Points on Different days
According to the color shades we can see that on an average, a taxi takes more time to travel a particular distance on weekdays, while the traffic on weekends is comparatively less especially on Sunday. Moreover, it takes more time to travel during the night and very less time during early morning. The possible reasons could be office hours, late night parties and night clubs etc. and people preferring to relax at home on Weekends.

Correlation between Different Time Durations
The correlation matrix shows a positive correlation between all the time durations except for Early Morning. That means that if on one particular day, it takes me more time to travel the distance, then it is more likely to take more time than usual at any other time of the day too except for early morning.
Yearly Trends of Daily Travel Time
The yearly trends show that the average daily time taken has somewhat a slightly decreasing trend and that of 2017 has a slightly increasing trend along with the linear models depicting this and the R squared values.

Trend in Data and Forecasting
We can see that the average daily travel time is fluctuating close to its mean value, and hence the forecast for the next year also shows a similar trend with a range of values it might fluctuate in given by blue shaded area.

Maximum and Minimum Time taken during Different Time Durations over Months
There is no significant difference in the upper and lower time bound of various time durations. The only observable difference is in the maximum time taken during various time durations in 2016. This mainly seems to be more stable in 2017 maybe because of the development of roads and traffic, many more taxis being introduced in 2017 and people using it more conveniently etc.

Comparison of Travel Time during Different Months
We observe that there is no significant difference between average daily travel time during different months. All of them revolve around 45-48 minutes.

Number of taxis segregated by Travel Time by Intervals
In these series of graphs, we can estimate the population of taxis and travel time on any day of the week segregated by adjustable time intervals using the bins parameter respectively.
Consider the situation where I need to make it to the destination a Sunday neither too early nor too late. A margin of 10 min early/late seems to be fine. So I put a bin size of 10 in the PM bins parameter and look for the value in the Blue colored bins signifying Sunday. Here we can predict that it is possible to cover these 14.8 km ( approx.) distance in no less that 30-40 minutes.
Similarly we can estimate the travel time and frequency of cabs available for other time slots and days as well.

Dashboard 1 : https://public.tableau.com/app/profile/viz.zards/viz/Viz-Zards/Dashboard1

Dashboard 2 : https://public.tableau.com/app/profile/viz.zards/viz/Viz-Zards/Dashboard2

Dashboard 3 : https://public.tableau.com/app/profile/viz.zards/viz/Viz-Zards/Dashboard3



