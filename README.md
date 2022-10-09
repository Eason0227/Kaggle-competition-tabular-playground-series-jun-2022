# Kaggle-competition-tabular-playground-series-jun-2022

For this challenge, you are given (simulated) manufacturing control data that contains missing values due to electronic errors. Your task is to predict the values of all missing data in this dataset.  

## Data Analysis Step 

EDA :
* Checking Missing degree of each features 
* Histograms of each features 
* Correlation between all features

Imputation :
* Split data to two part  
    Data with no missing values as training data  
    Data with missing values as testing data
* Calculate the number of missing values for each feature in testing data.
* Remove features with missing values in testing data.
* Remove features with missing values as X for training data, features with missing values as Y for training data.
* Training data is further divided into training and validation data
* Bulid the Neural Network Model to predict missing value.

