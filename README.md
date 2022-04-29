# Financial Planner App
 
This is a tool that will allow users to plan for financial emergencies by visualizing the investments in their wallet. 

It can be used to determine how much reserve funds they have and what they are comprised of. <br />

 
## Technologies
 
This project leverages python 3.7 and MCForecastTools
 
<br />
 
## Installation Guide
 
Before running the application first install/import the following.<br />

-Install pandas <br />
-Import the following: os, requests, pandas, alpaca_trade_api, dotenv, MCForecastTools. <br />
 
## Findings/Analysis 

APIs were first called to determine the price of two coins I used as examples, ETH and BTC. The value of these coins were then determined in USD and calculated accordingly with the amount of coins held in the wallet to produce a value for total holdings for crypto. This was then repeated for the stock values for SPY and AGG's closing prices as examples. These values were then added together to provide a total portfolio value. <br />
A savings dataframe was then created to calculate and visualize what assets made up the total portfolio value in order to determine if the current portfolio has enough to create an emergency fund. The MCSimulation was used to run a Monte Carlo simulation of 500 samples of the user's savings portfolio to visualize and forecast this data to see if the user should invest more towards stocks/bonds or crypto. 
<br />
 
## Contributors
 
Jeffrey Liu : Dev
UCB Fintech - Provided initial resources<br />

## License
Trilogy Technology 
UCB Fintech Extension Program
