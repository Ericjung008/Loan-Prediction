# Loan Prediction
This is a project assigned to me during [theDevMasters](https://www.thedevmasters.com) bootcamp.<br> 

## Introduction
With a large number of customers defaulting on their loans, banks are losing revenue. On the contrary, banks that are too cautious in issuing loans lose out on 
potential profit. With machine learning, customers who have a high risk of defaulting on their loans can be predicted. The prediction enables banks to issue loans, reject loans, or give higher interest rate loans to specific customers.

## Objective
The objective of this project is to predict which customer will default or pay his/her loan.

## Metrics 
The F1 Score was used as the evaluation metric for this project. The metric score indicates the harmonic mean between precision and recall.

## Approach
The following steps were taken to complete the project:
1. Import libraries and datasets
2. Cleaning Data
3. Analyzing Target Variable
4. Imputing Missing Values
5. Creating New Features
6. Encoding
7. Selecting Best Model
8. Optimizing Threshold
9. Visualizing Five Best Features

## Model Selection
The model was chosen based on the highest Receiver Operating Characteristic Area Under the Curve score.

<img width="558" alt="Screen Shot 2020-07-19 at 11 22 02 AM" src="https://user-images.githubusercontent.com/51253177/87882055-49ef4280-c9b2-11ea-88c4-fb0af6267314.png">

## Technologies
Application: Jupyter Notebook<br>
Programming Language: Python 3.7.4<br>
Libraries: Numpy, Pandas, Scipy, Matplotlib, Seaborn, Scikit-learn, XGBoost<br>

## Project Files
* [README](https://github.com/Ericjung008/Loan-Prediction/commit/bcb39946ae007aaefd5e42e8392bff7673ca2ff1)
* [Project](https://github.com/Ericjung008/Loan-Prediction/blob/master/Loan.ipynb)
* [Train Dataset](https://github.com/Ericjung008/Loan-Prediction/blob/master/Loan.csv.zip)
* [Data Dictionary](https://github.com/Ericjung008/Loan-Prediction/blob/master/loan%20data%20dictionary.docx)
