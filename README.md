# Project 1: 2021-2022 US Representative Stock Purchase Analysis

## Table of Contents

- [Presentation](#presentation)
- [About](#about)
- [Summary](#summary)
- [Conslusions](#conclusions)

## Presentation
[Prensentation Link](https://docs.google.com/presentation/d/1566EIw72dbnHjdzGT4L8z6EjFDt7xXnrDXf92rDtq6I/edit#slide=id.g207732c85b3_0_87)

## About
- How do we find data to analyze the stock trades of US Representatives? 
  - https://housestockwatcher.com/api
  - https://www.capitoltrades.com/committees - initially tried pulling our data from here but realized we needed to learn sophisticated web scraping techniques so we pivoted.
- Can we merge stock price data by utilizing the yfinance library to determine any trends throughout the year? 
  - yfinance is a popular open source library to access the financial data available on Yahoo Finance
- How many stock purchases did each of these representatives make and can we filter these by industry, sector, ticker, and party?
- Can we find any evidence of insider trading?
  - Is there a correlation between membership on a particular committee and stock trades in related companies?
  - Does any major buying or selling take place right before significant percent changes in stock price?
  - How do we remain unbiased in our analysis?
- Utilized the Python random function to select 6 random US Representatives. Each time the we run the code it continues to output these at random. 
  - Due to the makeup of the House, it will not always give an equal number of major party representatives.

## Summary


## Conclusions
- How do we remain unbiased? 
  - In an effort to try to remain unbiased, we randomized the representatives in each analysis. This can cause the analysis to be a bit skewed towards Republicans or Democrats since it is not always equal. In the future it might be more efficient to pick equal Republicans and Democrats. 
- How do we view the data from a high level?
  - We were able to visualize the party distribution, number of stock purchases, the sector, the industry, and top stock purchases for each representative. 
  - This can be used at the start of each analysis to get a better understanding of each representative’s trades to then dive deeper.
What did we learn from the deeper dive?
- Limitations of the Dataset:
  - The dataset did not have the exact purchase/sell price for the US representative’s trades. If we had this information we could analyze the % increase and decrease of each trade. 
  - The purchase/sell price could also allow us to determine the gains/losses for each representative.
  - 14% of the stocks came through empty within the data (49 total).


