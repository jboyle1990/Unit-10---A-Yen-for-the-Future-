# Unit-10---A-Yen-for-the-Future-
HW for Unit 10


## Introduction

This assignment was to use various sets of time series models to analyze Yen data from 1979 to 2019. We cleaned the data and filtered to build a dataframe of information from 1990 to 2019. We then analyzed our data to determine the following:

1. If we should invest in the Yen 
2. How do our models perform?

We used various different models to answer thse questions that can be found in two separate notebooks. These processes are outlined below.

## Notebook 1 - Time Series Forecasting

1. Decomposition using a Hodrick - Prescott Filter
2. Forecasting Returns using a ARMA Model
3. Forecasting the Settle Price with an ARIMA Model
4. Forecasting Volatility with Garch



## Notebook 2 - Linear Regression Forecasting

1. Using a Linear Regression Model
2. Using the testing data
3. analyzing in sample performance
4. analyzing out of sample performance


## Conclusions

### Linear Regression Analysis
Our models perform much better with out of sample data than using the in sample data. We can confirm this as fact due to the Out of Sample Root Mean Squared figure being 50% lower than the In Sample figure. There is a much lower variance with the out of sample data, thus confirming that our model performs better with this data.

### Time Series Analysis
It looks to be a good time to buy the yen based on the ARIMA model. This model is showing that the price of the Yen is projected to increase over our forecast timeframe.

Garch is showing that the volatility is expected to increase. This can be a good thing for an investment as larger swings in pricing can mean upside for our inveestment.

The P values are still too high for me to consider using these models for trading. While they show potential upside in the Yen I cannot confidentally rely on these models to make investments or provide investment advice. 

### Reccomendations 
I would try expanding the data sets to utilize other data sources in an attempt to fine tune the models. 

Overall, more work needs to be conducted on our models so that we can use them for analyzing potential trades in the future.
