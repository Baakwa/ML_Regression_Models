# Time Series Forecasting & Predictive Model Building for Store Sales at Favorita Grocery Retailer.

# Business Understanding 
Corporation Favorita a large and popular grocery retailer in Ecuador is seeking to enhance its sales forcasting capabilities for all items in the store. Accurate predictions of sales is important for effective inventory management, optimizing promotional strategies,improving resuorce allocationand enhanicng decision making. In order to do this, a robust  time series model that can predict the unit sales of items will be developed. The model will leverage on historical data including dates,store information, product details and promotion indicators to provide insights into sales patterrn for the future.

## Objectives
The goal for this project is to build a robust time series forcasting model that can accurately predict the unit sales of items in the store.

## Dataset
**Train.csv**:
This data comprises of time series features including store_nbr, family, and onpromotion as well as the target sales.

**Test.csv**
This data has the same features as the training data. Target sales will be predicted for the dates in thsi file.

**transaction.csv**
This data contains date, store_nbr and transactions made on that specific date.

**oil.csv**
This data contains the daily oil price which includes values during both the train and test data timeframes.

**holidays_events.csv**
This data contains Holidays and Events, with metadata. A transferred day is more like a normal day than a holiday.

**Additional information**
Wages in the public sector are paid every two weeks on the 15th and on the last day of the month.

A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.

## Hypothesis
Null Hypothesis: The promotional activities do not have a significant impact on store sales at Corporation Favorita.

Alternative Hypothesis: The promotional activities  have a significant impact on store sales at Corporation Favorita.


## Analytical Questions
1. Which dates have the lowest and highest sales for each year?
2. Did the earthquake impact sales?
3. What is the correlation between promotion frequency and total sales for each store?
4. What is the sales trend by year, month, week and day?
5. What is the overall sales trend?
6. What is the sales distribution across different stores clusters?
7. What product families contribute the most to the overall sales across all stores?

# Data Preparation
The various datasets mergerd then explored ,cleaned and preprocessed for modeling.

# Modeling & Evaluation of Models
Four models were trained for the prediction of sales.These models included linear regression, Decision tree regression, gradient booster, SDG regressor and ARIMA model. Random Forest regressor was the best performing models.

# Results


# Links
   
This repository talks about regression model for a time series forcasting problem

