# Grandmasters-of-Chess
This projects aims to see a trend in the growth of different Chess Grandmasters for each country starting from 1980. The dataset used for this project was Chessgames, which is a master database for all the notable chess masters that ever existed. 

### Executive Summary
This notebook analyzes the global scenarios in the field of playing chess; comparison of winning percentage of players, games played, and other demographics between each country all over the world. Even though chess is an individual game, the performance per country also provides significant insights. It then focuses on the best country to provide understanding and conclusion on how this country dominated the world of chess.

We analyze this by using data from **Chessgames.com**. This site maintains a large database of chess games which claims to be the biggest and popular online chess dataset and community. We used `BeautifulSoup` to scrape the data from two of its primary webpages having different outputs for different player identification numbers, which are, Player Biography and Player Game Database. After scraping, data preprocessing techniques such as restructuring, cleaning and text extraction, which was primarily conducted using `Pandas` and `RegEx`. Finally, the clean and manipulated data was stored in `SQLite3` Database. 

The data stored in SQLite3 were made into need-based DataFrames and performed Exploratory Data Analysis, primarily to understand the nature of data from statistical point of view. To understand the global scenarios, we conducted interactive geospatial analysis using `Folium`, that provides an intuition on dominating countries. This provided insights on the dominating country and in the end, determine the characteristics of that country's players and provides a concise overview on how Russians are currently dominating in terms of the amount of Chess Grandmasters based on the current dataset. 

### Problem Statement
Determine the dominating country in the world of chess, provide insights on its players, to understand why they became the strongest chess nation.

### Highlights of Result

1. Average winning rate of the nation is 37%
2. Most of the prominent players belong to the northern hemisphere
3. There are more Male prominent players in Chess than Female Prominent Players

##### The overall project can be explored in The Master of Chess Jupyter Notebook
