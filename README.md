# Stock-Strategies

This program generated buy and sell signals based on multiple signal strategies such as buy/sell thresholds, moving averages, directional indicators, etc. I utilized the Alpha Vantage API to retrieve historical data about stock trades in relation to the company inputted by the user. 

This program does the following:
1. Gets the user's input about which stock they want information on and which buying-and-selling strategy they want to use.
2. Downloads the relevant information about the stock from the API.
3. Calculates the user's chosen _indicator_ for each trading day in that stock. _Indicators work by aggregating price information for multiple days together into single values that broadly describe what happened across those days._ 
4. Determines the days on which the user's chosen signal strategy would have decided to buy or sell the stock.
5. Prints a detailed report of the analysis.

