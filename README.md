# Impacts on Field Goals Made Per Game



### Intro
Every NBA front office has a great interest in trying to get the best players they can possibly get in order to win more games and ultimately the NBA Finals. A great indicator for a great player is measured by the number of field goals made per game by a player throughout a full season. The higher the number of field goals made by a player, the better the player is perceived to be. Examining various basketball statistics, player measurements, and player background information can give front offices information on which variables relate to and impact field goals made per game the most. As a result, executives can use that information to make transactions to increase the performance of their team.

In this project, we utilized data on basketball statistics, measurements, and background information of players from the 2019-20 season and examined the role that various statistics, measurements, and background information have on a player's field goals made per game. 


### Data
This project uses two primary sources of data: Kaggle data on NBA players from the 1996-97 season through the 2020-21 season, and Basketball-Reference data for NBA players in the 2019-20 season.


### Getting Started
These instructions will get you a copy of the project up and running on you local machine for development and testing purposes.
1. Download the all_seasons_project.csv file and extract to desktop
2. Download the Impacts on Field Goals Made Per Game.R file and extract to desktop
3. Set working directory to extracted folder\Data


### Prerequisites
What things you need to run the software
1. R 3.3.2
2. RStudio 1.0.135
3. install. packages should not be in your script. library(package) is necessary.
4. Packages to install: xml2, ggplot2, dplyr.


### Script Initial Steps
1. Read the csv file which is a data frame gotten from Kaggle
2. Subset the dataframe
3. Web scrape data from basketball-reference website
4. This will get the player names in a data frame
5. This will get field goals made per game in a data frame
6. Vertical Integration to put all the players and field goals made per game in one data frame
7. Horizontal Integration to put all the stats, measurements, background information, and field goals made per game into 1 data frame
8. Converted field goals made per game into a numeric category
9. Sorted the data frame in order of most field goals made per game
10. Nulled the columns that were not used in the questions


### Questions
Question 1: Is there a significant correlation between the amount of games played, assists, and rebounds per game by each player and the field goals made per game that they have?

Question 2: Do Americans or Non-Americans tend to have higher field goals made per game?

Question 3: Do players that went to American colleges or did not go to American colleges tend to have higher field goals made per game?

Question 4: What is the relationship between a player’s age, height, and weight with field goals made per game?

Question 5: Does net rating, true shooting percentage, or usage percentage have the highest correlation with field goals made per game?

### Graphs
From ggplot: Scatter Plot

From dplyr: Boxplot

### Methodologies
1. Web Scraping
2. Correlation
3. Correlation Test
4. T.Test
