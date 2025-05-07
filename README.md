# Retail Analysis 

This repo shows a Jupyter Notebook that I used to analyze the retail data thoroughly. The data is get from Kaggle which describing products in each order. The data contains 50.000 rows, covers 4 years. The goal of this project is to analyze different aspects of this data, segment customers, 
,build sale prediction models and give recommendations to increase business performance. 

The notebook structures as follow: 

1. Data cleaning: prepare clean data for analysis
2. EDA: dive deepr into data in many aspects: Orders, Time of Orders, Shipment, Product, Sale at Loss, Customer, and Segmentation with KMeans
3. Sale prediction: build 3 models which are XGBoost, LSTM, Prophet. XGBoost is the best performance model, achieved **1.5% MAPE**. 

### Dependencies
Choose the lastest versions of any of the dependencies below: 
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [sklearn](https://scikit-learn.org/stable/)
- [tensorflow](https://www.tensorflow.org/)
