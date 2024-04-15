# Car-Price-Prediction-System
This repo is a about an ML Project which predicts Car Price based on features such as Name, Company, Fuel Type etc.Model which is used for training is Multiple Linear Regression Getting us an R2 Score  of 88

## Car Price Prediction Pipeline
## 1. Data Collection :
* Gather data on car features such as name, company, fuel type, etc., and their corresponding prices.
* All the data was scraped from Quikr.com.

## 2. Data Preprocessing :
* Clean the data by handling missing values,duplicates,datatype correction,vague data, outliers, and inconsistencies.
  
## 3. Exploratory Data Analysis (EDA) :
* Explore and visualize the relationships between different features and the target variable (Car Price).
* EDA  helps us to get valuable insights about  the data and outliers are easily spotted.
* Box Plots,Dist Plots,Histograms and Scatter Plots  were used for the same purpose.

## 4.Feature Engineering :
* Feature Transformation was done to get approx normalize curve of price column as Algorithms work better on normalized curve
* Categorical variables were converted into numerical format using one-hot encoding to make them compatible with machine learning algorithm
* Scaling was done to ensure that all features have the same scale.

## 5. Data Splitting :
* Split the dataset into training and testing sets.
## 6.Model Training :
* We choose Multiple Linear Regresiion Model to train the model.

# 7. Model Evaluation :
* Model's performance was evaluated  using the R2 score.
* Our R2 Score : 0.87
# 8. Result Visualization :
* Plotted Actual Vs Predicted Price Chart
