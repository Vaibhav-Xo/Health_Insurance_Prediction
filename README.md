# Health_Insurance_Prediction
![health-insurance-plan](https://github.com/Vaibhav-Xo/Health_Insurance_Prediction/assets/172389348/3b67c9e1-1e5a-49f5-b370-c3cd4f1a3c08)

# Project Objective
The objective is to create an ML model that accurately predicts individual's health insurance price based on some parameter like age, gender, bmi, children, smoking status, location. 

# About Dataset 
The dataset consist insurance records of an local Health Insurance company based in London. The dataset consist of 1340 records spread across 7 features (age, gender, bmi, children, smoking status, location, health insuarnce price). The target column is health insuarnce price.  

# Steps Involved 
## 1] Data Exploration 
* Loading dataset
* Checking shape 
* Checking duplicate records 
* Checking null values
* checking outliers 

## 2] Data Preprocessing 
* Handling Missing Values(Complete Case Analysis Technique)
* Handling Outliers(IQR Technique)

## 3] Exploratory Data Analysis
* Univariate Analysis(Histogram, Countplots, Boxplot, PieCharts)
* Bivariate Analysis(Scatterplot, Lineplot, Boxplot, Barplot)
* Multivariate Analysis(Pairplot)

## 4] Feature Engineering
* Feature Encoding(OneHotEncoder)
* Feature Scaling(StandardScaler)
* Feature Selection(Backward Feature Selection)

## 5] Model Training and Testing
* Linear Regressor
* SGD Regressor 
* KNN Regressor
* Decision Tree Regressor
* Random Forest Regressor
* SVM Regresoor
* XGB Regressor 
* AdaBoost Regressor 
* Gradient Descent Regressor

## 6] Peformance Metrics Used
* MSE 
* R2_Score 
* Cross Valve Score 

# Conclusion 
Gradient Decent Regressor was the best performing model with cross valve score of 86%.
