# DATA115 Personal Dataset Project

My Personal Dataset Project

## Motivation

As an avid sports fan all my life, I have always enjoyed watching sports and it was a passion for me. One of my favorite sports to watch is professional basketball and the NBA. Recently, the NBA has gone through a mini revolution on how the sport is being played, one that is unfamilar to me and many fans like myself. That is, the emergence of the three point shot. I, as well as many others, contribute this revolution to Stephen Curry and the 2015-2016 Golden State Warriors. I wanted to see in depth, how the greatness of Steph Curry and the Warriors have changed the NBA.

## Data Source

All data provided below is collected from basketballreference.com

## Processing

First, collecting the data was very simple as basketballreference.com provides an ongoing database for all NBA stats. Processing the data was not very difficult thanks to the convienence provided from the basketball reference database. For all the plots shown below, I used a similar procedure to process my data. I started off by sorting the data in descending order from most three pointers attempted to the least. Then, I used the feature on basketball reference that allowed me to delete columns to filter out unwanted data. For some plots, I also deleted rows in order to show the players or teams that were at the top that season. From there, I created multiple .csv files for my respective visuals and inputted these files to Excel and R. In Excel, I plotted boxplots with multiple categorical variables to show the shot breakdown in comparing seasons. In R, I made a simple boxplots to show the Warriors team that began the revelation of the modern NBA. I also used R to conduct exploratory data analysis by comparing boxplots of two seasons.

## Visuals

Before we go in-depth on how the NBA has changed in recent years, I wanted to show a shot breakdown of the team responsible for this change, the 2015-2016 Golden State Warriors. I conducted a bar graph highlighting the top 5 three point shooters on that team lead by Steph Curry and WSU's own, Klay Thompson.

<img src="https://raw.githubusercontent.com/alan-pan31/DATA/main/Warriors%20Top%203PA.png">

Below is a barplot visualizing the top 5 teams that led the league in three point attempts in the 2015-2016 season compared with their two point attempts. As you can see below, the Warriors lead the league at three point attempts at 31.6 attempts per game, compared to 55.7 two point attempts. The Dallas Mavericks rounded out the top 5 with 28.6 3PA and 55.6 2PA respectively.

<img src="https://raw.githubusercontent.com/alan-pan31/DATA/main/2015-2016%20NBA%20Shot%20Breakdown.png">

Now, lets show how the shot breakdown has changed in the most recent full season of the NBA. In the 2019-2020 NBA season, the Houston Rockets led the league with 45.3 3PA and 45.2 2PA. Even the 5th team, the Brooklyn Nets, attempted 38.1 3PA, almost ten more three points attempted per game than the 5th team in the 2015-2016 season.

<img src="https://raw.githubusercontent.com/alan-pan31/DATA/main/2019-2020%20NBA%20Shot%20Breakdown.png">

## Analysis

In my analysis, I compared the average 3PA per game for every team in the 2015-2016 season with the 2019-2020 season to provide a visual of how the shot breakdown has changed in just four years. As you can see, the distrubution has increased quite dramatically. The distrubution showed that not only did the mean increase, but the whole distrubution of data increased. For example, the minimum amount in the 2019-2020 season is almost aligned with the third quandrant or the 75th percentile of the 2015-2016 plot. Lastly, the plots showed that the dispersion of data was narrowed in the 2019-2020 season. This meant that more and more teams were regularly shooting threes at a high volume compared to the 2015-2016 season, where only a few teams were shooting at a high volume.

<img src="https://raw.githubusercontent.com/alan-pan31/DATA/main/Exploratory%20Analysis.png">

