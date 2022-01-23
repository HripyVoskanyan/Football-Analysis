# Football-Analysis
This project tries to understand the impact of home team advantage during the COVID lockdown.

“Home team advantage” concept is familiar to many people who watch or play sports. 
It is about having an advantage and more chances to win the match when the team hosts in their field. The reasons of this phenomenon are not completely clear, however they include but are not excluded to field familiarity, comfort, travel effects, fan presence. The latter is considered to be the most significant factor. During the COVID-19 pandemic, restrictions were held all over the world and sports were not exceptions. 
Because of the situation, leagues started playing “ghost games”: games without any fans on the stadium. This had impact on the scores of major leagues, thus an analysis on how much the presence of supporters change the results of the game is useful to do. 
That will help to understand whether the home advantage really exists and how much of it depends on the presence of fans. 

# Research Methodology
The data was taken from this source: https://github.com/bicachu/EPL-fans-presence-experiment/tree/main/data. The
author used Selenium for Python scraper to get the data from the official website of the Premier League.
The scraper took:

• Overall match events (number of yellow/red cards, passes, off-sides, etc.)

• Scores

• Goal information

So the whole data is quantitative(except the names of teams) and easy to use.
In order to use this in the project, various R packages were used to reprocess the data, analyze, and visualize
to get necessary results. These include libraries dplyr and ggplot.
