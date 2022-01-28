# Demand-Forecasting-of-Retail-Store-Items


The objective of the problem is to forecast 3 months of sales for 50 different items at 10 different stores using the 5 years history of sales.

### Dataset:
https://www.kaggle.com/c/demand-forecasting-kernels-only/data

The data contains the following files:

- train.csv : the training data witht the history of sales.

- test.csv: the test data to predict the sales.

### Data fields

- date - Date of the sale data. There are no holiday effects or store closures.

- store - Store ID

- item - Item ID

- sales - Number of items sold at a particular store on a particular date.

### Introduction:
Time series forecasting is a skill that few people claim to know. Machine learning is cool. And there are a lot of people interested in becoming a machine learning expert. But forecasting is something that is a little domain specific.

Retailers like Walmart, Target use forecasting systems and tools to replenish their products in the stores. An excellent forecast system helps in winning the other pipelines of the supply chain. If you are good at predicting the sale of items in the store, you can plan your inventory count well. You can plan your assortment well.

A good forecast leads to a series of wins in the other pipelines in the supply chain.


### What is the difference between a time series and a normal series?
Time component is important here. The time series is dependent on the time. However a normal series say 1, 2, 3...100 has no time component to it. When the value that a series will take depends on the time it was recorded, it is a time series.

### Steps:

1. Load Libraries
2. Load Data, Summary
3. Missing Values
4. Individual Feature Visualization
4.3 Sales growth monthly
4.4 Growth by Year
4.5 Sales growth by store
4.6 Yearly Growth by Item
5. Prophet Model
5.8 SMAPE Calcuation
5.9 Automated forecasting with Prophet: Splitting data by store and item
