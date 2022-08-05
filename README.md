# European_Soccer_Analysis
Exploratory Data Analysis of European Soccer from the years 2008/2009 to the 2015/2016 season

<a id='intro'></a>
## Introduction

### Dataset Description 📜

The dataset we shall be using in this project is the [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) ⚽. It contains data from soccer matches, players, and teams from several European countries which runs from 2008/2009 to 2015/2016 season. Originally it is available as an sql database but I managed to get the tables as ".csv" from [Udacity](https://www.udacity.com/).
The tables provided include:

|Table	  |Total Rows|Total Columns|
|:--------|----------|------------:|              
|Country         |11	|2|
|League |11	|3|
|Match	|25979|115|
|Player	|11060|7|
|Player_Attributes|183978|42|
|Team	|299	|5|
|Team_Attributes|	1458|	25|

These tables combined provide information on:
- +25,000 matches
- +10,000 players
- 11 European Countries with their lead championship
- Seasons 2008 to 2016
- Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
- Team line up with squad formation (X, Y coordinates)
- Betting odds from up to 10 providers
- Detailed match events (goal types, possession, corner, cross, fouls, cards etc…) for +10,000 matches

<a name='questions'></a>
### Questions for Analysis  🔎

  **A) Season-specific analysis**
  > Case Study : **2️⃣0️⃣1️⃣5️⃣ / 2️⃣0️⃣1️⃣6️⃣ season**
  >
  > 🗣️ _Here we shall be focusing on events that occured during the 2015/2016 season across all leagues_
    
    1) Which league witnessed the most goals?
    2) Were the non-tie matches generally won by the home team? (Note: A non-tie match is one which has a winner)
    

  **B) League-specific Analysis**
   > Case Study : **English Premier League (EPL) 🏴󠁧󠁢󠁥󠁮󠁧󠁿**
   >
   > 🗣️ _Here we shall be focusing on events that occured in the EPL across all seasons_

    3) Which season recorded the least draws? 
    4) Who are the highest league winners?
    5) Does the top scoring team generally win the league?
