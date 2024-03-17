## Nifty50 Constituents

### A. About
This project is about analysing Nifty50 constituents over time here: https://www.niftyindices.com/indices/equity/broad-based-indices/NIFTY-50. 

Specifically, there are some areas we can analyse on Nifty50 constituents which gives us valuable insights. These areas are:
1. Calculate Simple moving average for Equity Capital of Tickers over past 6 months window
2. Calculate year wise high and low Equity Capital for each stock
3. Find 2 tickers with highest positive correlation in prices movement and 2 tickers with highest inverse correlation

Before we can even analyse the data, there is a need to create our database schema such that we can reliably store data into it and preprocess it afterwards as well. Please see ```main.ipynb``` for more information

### B. Tech Stacks
1. ```Python``` - main scripting language for easy analysis and interaction with our DB schema
2. ```SQLite``` - simple storage service for small medium sized data and allowing users to write SQL queries from Python

