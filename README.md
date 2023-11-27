# Credit Card Fraud Detection

The dataset contains transactions made by credit cards in September 2013 by European cardholders.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

In this project, I will use various predictive models and compare their performance in detecting whether a transaction is a normal payment or a fraud.

Specifically, the goals in this project include:

1. Dataset EDA
   
   ![image](https://github.com/huongnd12/credit-card-fraud-detection/assets/57044034/6b7e3d74-e908-4ef3-bfc2-274b37332d87)

3. Dealing with imbalanced data between Fraud and Non-Fraud transactions with SMOTE oversampling technique
4. Training with classifiers (K-Nearest Neighbors, Random Forest, XGBoost, Logistic Regression) and comparing their evaluation metrics
5. Applying a fully-connected neural network for classification 
