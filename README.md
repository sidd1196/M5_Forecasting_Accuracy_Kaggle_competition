# M5-Forecasting---Accuracy Top 10 % solution


## Business Problem :-
M5 Forecasting Accuracy is a competetion in which we have to forecast future sales of each
product in each store based on the hierarchical sales data provided by Walmart. In this
competetion we have to forecast daily sales for next 28 days. Here we have the data for 3 states in
US(California, Texas, and Wisconsin). The data files (.csv files) provided for the competetion
consists of item level, department, product categories,items sold on a day, store details, price,
promotions, day of the week, and special events. So by using this data we will forecast daily sales
for next 28 days as accurately as possible.


## ML formulation :-
We will do some data preprocessing and feature engineering to get desired format and some new
features respectively . Once the data is ready we will pass it through different machine learning
and deep learning models . After the model is trained we will predict the values for test dataset. We
will pose this as a supervised machine learning regression problem. In this problem we will be
using LGBMRegressor and XGBoost regressor models.


## .ipynb Notebooks :-

1. M5_forecasting_Accuray_EDA_3.ipynb - In notebook I have performed data analysis and data visualization to get some insights from the data.
 *notebook - https://nbviewer.jupyter.org/github/sidd1196/M5_Forecasting_Accuracy_Kaggle_competition/blob/main/M5_forecasting_Accuray_EDA_3.ipynb


2. M5_Forecasting_Accuracy_Data_Preprocessing_and_Modelling_Final_2.ipynb - In this notebook I have done data preprocessing , feature engineering and then I used different ML models and different techniques for predicting the sales for validation and test dataset.
 *notebook - https://nbviewer.jupyter.org/github/sidd1196/M5_Forecasting_Accuracy_Kaggle_competition/blob/main/M5_Forecasting_Accuracy_Data_Preprocessing_and_Modelling_Final_2.ipynb


*noteboook - if you are not able to open the .ipynb file click on the link provided.
