# TATA Motors Stock Close Price Prediction Model

## Introduction
This project aims to predict the closing price of TATA Motors stock using various machine learning algorithms and technical indicators. The data used for this project ranges from 1999 to 2023.

## Libraries Used
The following libraries are used in this project:
- pandas for data manipulation and analysis
- yfinance for downloading stock data from Yahoo Finance
- numpy for mathematical operations
- matplotlib and seaborn for plotting and visualization
- plotly for interactive charts
- cufflinks for creating charts using pandas dataframes
- warnings for ignoring warnings
- sklearn for machine learning algorithms and evaluation metrics

## Data Collection and Exploration
The data for TATA Motors stock is collected from yfinance library and the start and end dates are set from 1999 to 2023. The data is then explored to understand the general characteristics and trends of the stock.

## Exploratory Data Analysis
The following exploratory data analysis techniques are used in this project:
- Calculation of mean, median, standard deviation, max and min of closing price
- Distribution of daily returns
- Candlestick chart to show the variation between the highest and lowest returns
- Moving average chart to show the trend of the closing price
- Correlation heatmap to show the relationship between different features
- Technical indicators such as simple moving average and Bollinger Bands to identify trends and volatility.

## Feature Engineering
The following features are engineered in this project:
- Weekly moving average for the Open Price
- Bollinger Bands for the Open Price

## Model Selection and Evaluation
The following machine learning algorithms are used in this project:
- Linear Regression
- Random Forest Regressor
- Support Vector Regression (SVR)
### Optional
Before training our models, we need to standardize our data to ensure that the scale of each feature is consistent. This is important because some algorithms are sensitive to the scale of the input data.To standardize the data, we will use the StandardScaler class from the scikit-learn library. This class will transform our data by subtracting the mean and dividing by the standard deviation.

The models are trained and tested using train-test split and the evaluation metrics used are R2 score
- R2 score for linear regression: 0.9988672659694222
- R2 score for random forest:  0.9986958832140901
- R2 score for SVR:  0.9900765820020023

The best performing model is selected based on the evaluation metrics.

### Based on the R2 scores, it appears that the linear regression model performed the best with an R2 score of 0.9988672659694222. 

## Model Prediction 
Linear Regression model will be used to predict the closing price of Tata Motors stock.After that, we will evaluate the model by checking the R2 score, mean absolute error, and mean squared error.We will then use this model to make predictions on the future closing prices of Tata Motors stock.Then Plot The Actual and Prediction Data Using The Scatter Plot


<div align="center">
<h3> Connect with me<a href="https://gifyu.com/image/Zy2f"><img src="https://github.com/milaan9/milaan9/blob/main/Handshake.gif" width="60"></a>
</h3> 
<p align="center">
    <a href="mailto:roshanguptark432@gmail.com" target="_blank"><img alt="Gmail" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Gmail.svg"></a> 
    <a href="https://www.linkedin.com/in/roshan-sinha/" target="_blank"><img alt="LinkedIn" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Linkedin.svg"></a>
    <a href="https://www.instagram.com/roshan_the_constant/?hl=en" target="_blank"><img alt="Instagram" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Instagram.svg"></a>
    <a href="https://www.hackerrank.com/roshanguptark432" target="_blank"><img alt="HackerRank" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/HackerRank.svg"></a>
    <a href="https://github.com/roshancharlie" target="_blank"><img src="https://cdn.svgporn.com/logos/github-icon.svg" alt="Github logo" width="25px"></a>
</p>  
