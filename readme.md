# Credit Card Fraud Detection

### Source: 
[Click Here](https://www.kaggle.com/mlg-ulb/creditcardfraud)

### Context:
It is important that credit card companies are able to recognize fraudulent credit card 
transactions so that customers are not charged for items that they did not purchase.

### Content:
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately,
due to confidentiality issues, we cannot provide the original features and more background information about the data.
Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount,
this feature can be used for example-dependant cost-senstive learning.
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

### Project overview
1.Exploratory Data Analysis (EDA)

2.Data Preprocessing and decomposition

3.Train and Test Split

3.Application of Machine Learning Algorithms (using scikit-learn for python)
    a)Logistic Regression
    b)Random Forest Classifier
    c)Naive Bayes Classifier
    d)Support Vector Machine
    
4.Results and Comparison.
