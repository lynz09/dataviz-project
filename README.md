# Dataviz Final Project - International Football Games

## Data

The data I propose to visualize for my project is the [International football results](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017).


## Prototypes


I’ve created a map that shows the cities' distribution of football games by latitude and longitude across the world from 2010 to 2020. 

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/map1.png)](https://vizhub.com/lynz09/2e0b2da3c6db4d70b40fe91c16a1897c)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

* Which countries host the most matches?
* Who is the best team of all time?
* Which teams dominated different eras of football?
* What trends have there been in international football throughout the ages - home advantage, total goals scored, distribution of teams' strength etc?
* Can we say anything about geopolitics from football fixtures - how has the number of countries changed, which teams like to play each other?
* How much, if at all, does hosting a major tournament help a country's chances in the tournament?

## Sketches

The following are my sketches of how the project will look like:

* show the places where FIFA World Cup matches have been played on a map.
* show the cumulative sum of matches for top teams.
* show the description of games per year: trend,common game type,etc.
* show the win and loss rates.


![image](https://github.com/lynz09/dataviz-project-proposal/blob/master/image/Screen%20Shot%202020-10-07%20at%209.58.01%20PM.png)

![image](https://github.com/lynz09/dataviz-project-proposal/blob/master/image/Screen%20Shot%202020-09-30%20at%2011.44.29%20PM.png)

![image](https://github.com/lynz09/dataviz-project-proposal/blob/master/image/Screen%20Shot%202020-09-30%20at%2011.44.54%20PM.png)

![image](https://github.com/lynz09/dataviz-project-proposal/blob/master/image/Screen%20Shot%202020-09-30%20at%2011.45.00%20PM.png)

## Ideas for Interaction

The final deliverables of project would have:

* World Map: In the world map, the user can zoom in and out to see where all world football matches have been played.
* Bar charts: In the bar chart of sketch 3, the user can select the number of games by different tournament and year.

## Schedule of delivrables

* World map: learn how to create a map where all world football matches have been played.(10/14/2020)
* Word map zoom in and out.(10/17/2020)
* Top teams: create the bar chart and show top 10 teams.(10/20/2020)
* Interaction the map and bar chart: make the map show data of that country.(10/27/2020)
* Description of games per year: draw the bar chart.(10/29/2020)
* Win and loss rates: Calculate the win and loss rates and rank top 10 teams according to win rates.(11/4/2020)
* Debugging and checking.(11/11/2020)

## Visualization

* visualization 1

This bar chart shows the top 10 countries that host the most international football games in the world. We can find the answer for question(Which countries host the most matches) from this plot that Mexico host the most matches between 2010 and 2020.

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/top10.png)](https://vizhub.com/lynz09/3a5b8ffb514d43d085e6253999f9f33f)

* visualization 2

A bar graph showing different types of football games/tournaments since 2010 to 2020 (a realization of my sketch 2). The X axis represents the Year, Y axis represents number of games. From this visualization, we can conclude which are the most common game type and comptetitions per year. We can see that some events/tournaments are more frequent on non-world cup years.The most common event is AFC Asian Cup.

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/tournament.png)](https://vizhub.com/lynz09/fb64231659cb4bce88c56efc6db68b1b)

* visualization 3

This scatter Plot shows the number of games per year where each tournament is held. I add interactive color legend to make it better than visualization 2. When you moves to every legend, you will see the number of matches for each tournament

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/interaction1.png)](https://vizhub.com/lynz09/7db68dc820614051ae5193edef30d93d)

* visualization 4

A world map showing locations that host the international football games between 2010 to 2020.

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/map1.png)](https://vizhub.com/lynz09/2e0b2da3c6db4d70b40fe91c16a1897c)

* visualization 5

The world map have these functions: zoom in/out, tooltips, hover over the data point for additional data. 

[![image](https://github.com/lynz09/dataviz-project/blob/master/image/map2.png)](https://vizhub.com/lynz09/ee5a4a11a34142689716dd8e85d83f60)


## Future work

* calculate the win and loss rates for each team 
* add the win and loss rates to visualization 5



