# Retail Analysis 

This repository contains a Jupyter Notebook used to perform a comprehensive retail analysis on a dataset from Kaggle. The dataset includes details on products in each order, with 50,000 rows spanning over four years. The goal of this project is to analyze various aspects of the data, segment customers, build sales prediction models, and provide actionable recommendations to improve business performance.

### Data Description

The dataset consists of 50,000 records over 4 years, detailing various aspects of retail transactions:

- Orders: Information on each customer’s order.
- Product Information: Details about the products in each order.
- Customer Data: Information related to customer demographics.
- Shipment: Delivery and shipping details.

### Notebook Structure

**1. Data cleaning:** prepare cleaned data for analysis

**2. EDA:** dive deeper into data in many aspects: 
- Revenue: Sale growth and sale pattern over time
- Orders: Volume of orders and AOV
- Time of Orders: Identifying peak and off-peak periods in years and weeks, Reorder period
- Shipment: Ship mode, order priority, and performance of delivery service.
- Product: Identify the stage of each product (Growth, Saturation,..), most important products
- Sale at loss: Reasons that many products are sold at loss
- Customer: Number of customer overtime, repeat customer
- Customer Segmentation: Using KMeans to group customer
- 
**3. Sale Prediction:**
- BiLSTM: Trained a network with 2 bidirectional LSTM layers, follows by 2 Dense layers and 2 Dropout. Using a custom loss function
- Prophet: Trained a Prophet with yearly and weekly seasonality
- XGBoost: Trained with 500 estimators, max_depth = 3, and subsample = 0.8. Achieved **1.5% MAPE**.

---> XGBoost is the best performance model

### Dependencies
Choose the lastest versions of any of the dependencies below: 
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [sklearn](https://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/)
- [xgboost](https://xgboost.readthedocs.io/en/release_3.0.0/)
- [prophet](https://facebook.github.io/prophet/)
