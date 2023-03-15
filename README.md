# Kaggle-competition-tabular-playground-series-jun-2022

For this challenge, you are given (simulated) manufacturing control data that contains missing values due to electronic errors. Your task is to predict the values of all missing data in this dataset.  

## Data Analysis Step 

EDA :
* Checking Missing degree of each features 
* Histograms of each features 
* Correlation between all features

Imputation :
* Split data to two part  
    * Data with no missing values as training data  
    * Data with missing values as testing data
* Calculate the number of missing values for each feature in testing data.
* Remove features with missing values in testing data.
* Remove features with missing values as X for training data, features with missing values as Y for training data.
* Training data is further divided into training and validation data
* Bulid the Neural Network Model to predict missing value.

Final submmition result :
* RMSE = 0.83554
* Rank = 45/844(Top 6%)
---
## 分析流程如下：  
1. EDA : 檢查每個特徵的缺失度、直方圖、特徵之間的相關性  
2. 將沒有缺失值的數據作為訓練數據，有缺失值的數據作為測試數據  
3. 計算測試數據中每個特徵的缺失值數量  
4. 刪除測試數據中該缺失值的特徵  
5. 在訓練數據中同樣移除該遺失值特徵作為X，訓練資料中該遺失值的特徵則為Y  
6. 進一步將訓練數據分為訓練數據和驗證數據  
7. 建立神經網絡模型來預測缺失值  
