# Module-11-Challenge

## The goal

The goal is to explore data around Mercado Libre. The data explored is time-series data.  

## Files

For this assignment we used google Co-lab and Meta's Prophet. The Prophet tool is used to make a forecast of future values of google search trends and revenue

A link to my co-lab notebook is below

[CO-LAB](https://colab.research.google.com/drive/1BpBDlLLlFBmMaxKciEcCtP_xteeWdQI0?usp=sharing)

a copy of my CO-LAB note book is in the repo: forecasting_net_prophet_jjo

## Output
    
### Stock Price
The stock price of Mercado Libre 
![stock](/Images/Stock_price.png)

The analysis here was to look at the stock price and compare it to the search traffic in the next section to see if there was an correlation to volatility or stock price

![vol](/Images/stock_vol.png)

here is a weak inverse relationship between lagged search and stock price. There is very little relationship between the stock price and the lagged search trends

### Search Traffic

![vol](/Images/output_trend.png)

The google search trends for Mercado Libre

a quick analysis on trends was done
![trend](/Images/Trend_by_day.png)

Then data was used to train the prophet tool 

Below is the output of the prophet tool to forecast the future outcomes. This data is based on google search trends.
![prophet](/Images/prophet.jpg)
    
### Revenue 

A similar analysis prophet analysis was done with with Revenue data. 

a quick forcast was done as part of the analysis. Here we wanted to determine the best/worse case and the most likely outcome. 

![rev](/Images/revenue.png)
    


