Credit Card Customer Segmentation using K-Means

Overview
This project uses K-Means Clustering to group credit card customers based on their financial behavior and spending patterns.

Dataset
The dataset contains the following features:
CUST_ID
BALANCE
BALANCE_FREQUENCY
PURCHASES
ONEOFF_PURCHASES
INSTALLMENTS_PURCHASES
CASH_ADVANCE
PURCHASES_FREQUENCY
ONEOFF_PURCHASES_FREQUENCY
PURCHASES_INSTALLMENTS_FREQUENCY
CASH_ADVANCE_FREQUENCY
CASH_ADVANCE_TRX
PURCHASES_TRX
CREDIT_LIMIT
PAYMENTS
MINIMUM_PAYMENTS
PRC_FULL_PAYMENT
TENURE

Steps
1-Data cleaning and preprocessing
2-Removed CUST_ID
3-Filled missing values using Mean Imputation
4-Applied StandardScaler
5-Performed EDA and visualization
6-Used Elbow Method and Silhouette Score to select K
7-Built the final K-Means model

Tools
Python
Pandas
Matplotlib
Scikit-learn
Scikit-learn
Jupyter Notebook
