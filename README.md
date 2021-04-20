## Comparison of Win Loss ratios for cities in each league within the USA big 4 (NBA, NHL, NFL, MLB)

This notebook is derived from my final assignment in the [Introduction to Data Science with Python](https://www.coursera.org/learn/python-data-analysis#syllabus) course offered by the University of Michigan on Coursera.

For this assignment, I was given a file of metropolitan regions and associated sports teams from [wikipedia_data.html](wikipedia_data.html). Each of these regions may have one or more teams from the "Big 4": NFL (football, in [nfl.csv](nfl.csv)), MLB (baseball, in [mlb.csv](mlb.csv)), NBA (basketball, in [nba.csv](nba.csv) or NHL (hockey, in [nhl.csv](nhl.csv)).

The main question I had to answer via my code was : **What is the `win/loss ratio`'s correlation with the `population` of the city it is in?**

`Win/Loss ratio` refers to the number of wins over the number of wins plus the number of losses. 
Correlation will be computed with the `pearson` method.
