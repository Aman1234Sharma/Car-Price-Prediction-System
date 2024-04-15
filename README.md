# Car-Price-Prediction-System
This repo is a about an ML Project which predicts Car Price based on features such as Name, Company, Fuel Type etc.
<br>
Model which is used for training is Multiple Linear Regression Getting us an R2 Score  of 88

## Car Price Prediction Pipeline
## 1. Data Collection:
* Gather data on car features such as name, company, fuel type, etc., and their corresponding prices.
* All the data was scraped from Quikr.com.

## 2. Data Preprocessing:
* Clean the data by handling missing values,duplicates,datatype correction,vague data, outliers, and inconsistencies.
  
2. Exploratory Data Analysis (EDA):
Data Visualization: Explore and visualize the relationships between different features and the target variable (Car Price).
Feature Engineering: Create new features, encode categorical variables, and normalize numerical features if necessary.
3. Data Splitting:
Train-Test Split: Split the dataset into training and testing sets to evaluate the model's performance.
4. Model Selection:
Multiple Linear Regression: Choose Multiple Linear Regression as the predictive model due to its simplicity and interpretability for this regression task.
5. Model Training:
Feature Selection: Select relevant features for training the Multiple Linear Regression model.
Training: Train the model using the training dataset to learn the relationships between the features and the target variable (Car Price).
6. Model Evaluation:
R2 Score: Evaluate the model's performance using the R2 score, which measures the proportion of the variance in the dependent variable that is predictable from the independent variables. Aim for an R2 score of 88% or higher as mentioned.
