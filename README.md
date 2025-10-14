# Analysis of board game data from board game geek

## Summary

Exploratory data analysis to discover whether popularity of a board game is correlated with it's complexity.    

The analysis shows that there is a slight positive correlation between Complexity and the Popularity (based on Ratings).
More complex games tend to be rated higher and highly rated games are slightly more complex.

## Data Sources
Data sourced from kaggle dataset [melissamonfared/board-games][data_source] which was sourced from [Board Game Geek][bgg_website]  
Data source was last updated in 2022

## Analysis   
### Scope   
The data shows an exponential increase in the board games created in the recent decades. Since the dataset was created around beginning of 2021, we see a drop in the count of games created.   
For the purpose of this exercise we will limit our analysis to the time period from 1950 to 2020.

The [jupyter notebook](./bgg_eda_popularity.ipynb) has the detailed steps of the analysis.  

This can also be found on Kaggle under [abinandsivakumar/bgg-eda-popularity](https://www.kaggle.com/code/abinandsivakumar/bgg-eda-popularity)

## Dashboard  
A [Power BI report](./Report.pbit) was created to visualize the correlation for a specific year or a range. 
Screenshot from the report:
![screenshot](https://github.com/user-attachments/assets/f919130a-fec2-46b4-a690-43cf4535efd6)

> To view the report in Power BI Desktop, download the [data source csv file][data_source] to a local path and enter the path in the parameter when prompted.

[bgg_website]: https://boardgamegeek.com
[data_source]: https://www.kaggle.com/datasets/melissamonfared/board-games/data
