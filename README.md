# Bikesharing Analysis

## Overview of the analysis
The purpose of this analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. We will be using Python (Jupyter Notebook) and Tableau to report our findings.

## Resources
Python
Jupyter Notebook
Tableau
Citi Bike Trip History - "201908-citibike-tripdata.csv"

## Results
We were given a csv file containing a lot of information about Citi Bike data. Below are the visualizations we came up with.

### Trip Duration
This visualization shows how long bikers generally take on each trip. This curve shows us that the majority take under 30 minutes, with the most common trip time of 5 minutes.

![tb1](https://user-images.githubusercontent.com/91795475/150721595-c0dada2b-4cb7-4395-bba3-1a1cd04c5f87.png)


### Trip Duration by Gender
This visualization is the same as the prior one, but filtered by gender. As we can see, males typically use the bikes significantly more than the other genders.

![tb 2](https://user-images.githubusercontent.com/91795475/150721607-490e9e7e-d303-4115-8a2b-9a8389a39fc9.png)


### Trip by Day
This visualization is a heatmap showing how busy the bikes are during different days of the week and times. This is important to know when peak hours occur and when there is more off-time for repairs.

![tb 3](https://user-images.githubusercontent.com/91795475/150721617-726e32b3-64e7-40de-b54e-2d76e50ca4dd.png)


### Trip by Day by Gender
This is the same visualization as the previous one, except it is filtered by gender. We can draw the same conclusions as before, that males seem to use the bikes the most and that each gender follows similar patterns as to when they use them.

![tb 4](https://user-images.githubusercontent.com/91795475/150721620-c39774bb-9434-4147-a441-45d7a8f1573b.png)


### Customers vs Subscribers
This visualization is derivative of the previous heatmap, but now we are looking at customers vs subscribers. Subscribers make up a significantly higher proportion of total users than do customers.

![tb 5](https://user-images.githubusercontent.com/91795475/150721625-55d42f60-d0f7-447c-a5d1-ae656e15daa8.png)


### Frequency by Hour
Sometimes a simple bar graph is the best description. Here we can see how many bikes are rented out at each hour of the day.

![tb 6](https://user-images.githubusercontent.com/91795475/150721632-1b94f942-fd4d-456c-b26c-06fd6b4fb130.png)


### Map
This map shows us where the bikes are being rented, and how many in each area.

![tb 7](https://user-images.githubusercontent.com/91795475/150721637-68ac4c08-4f9b-479f-88cb-7950232afbcf.png)

## Summary
These visualizations are key to understanding the big picture of expanding the citi-bike program to other cities. I would argue that data from other cities needs to be looked at, particularly the same exact visualizations we just did. Comparing New York to other cities needs to be looked at closely due to the fact that New York is unlike any other city on Earth because of many factors including its vast diversity. Other cities, like Des Moines, may not be similar enough to extrapolate these results. If we had data from more cities, the visualization possibilities are almost limitless. In particular, I would recommend box and whisker plots measuring trip time and each plot would be a city, and I would recommend a heatmap by hour with a filter for citites. I am curious to see if there would be a difference or if "The City that Never Sleeps" does not apply to bikesharing.


link to Tableau Dashboard: https://public.tableau.com/app/profile/daniel.martin2859
link to Tableau Challenge Assignment: https://public.tableau.com/app/profile/daniel.martin2859/viz/Module14ChallengeAssignment/BikesharingAnalysis
