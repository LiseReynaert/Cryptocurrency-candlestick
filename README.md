# Cryptocurrency-candlestick
### How to use CoinGecko API to create candlestick graphs

In this exercise, we use the <a href="https://www.coingecko.com/en/api?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2022-01-01">CoinGecko API</a> to create candlestick graphs for Bitcoin.

I will use the API to get the price data for 30 days with 24 observation per day, 1 per hour. We will find the max, min, open, and close price per day meaning we will have 30 candlesticks and use that to generate the candlestick graph. 

The Python client/wrapper for the API called <a href="https://github.com/man-c/pycoingecko?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2022-01-01">PyCoinGecko</a>  will make performing the requests easy and it will deal with the endpoint targeting.

### Table of Contents
0. [Settings](#0.Settings)
1. [Data collection](#1.Datacollection)
2. [Data Wrangling](#2.DataWrangling)
3. [Data Visualisation](#3.DataVisualisation)
