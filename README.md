# Australian Residential Property Price Forecasting Using Machine Learning and Time Series Analysis

## Project Overview

This project focuses on forecasting future residential property price growth across Australian capital cities using a hybrid analytical approach combining **time series forecasting** and **machine learning techniques**. The objective is to identify which Australian capital city is likely to experience the highest residential property price growth over the next three years.

## Business Problem

The Australian housing market is influenced by multiple economic factors, including historical price trends and inflation changes. This project aims to provide data-driven insights to support investors, policymakers, and businesses in understanding future property market movements and making informed decisions.

## Dataset

The project uses Australian residential property price data collected from the **Australian Bureau of Statistics (ABS)**, covering more than 20 years of historical market trends.

The dataset includes:

* Median residential property prices across eight Australian capital cities.
* Quarterly property price observations from 2002 to 2025.
* Consumer Price Index (CPI) data as an economic predictor.

## Data Preparation & Analysis

The data preparation process included:

* Data cleaning and validation.
* Reshaping datasets from wide format to long format.
* Combining housing price data with CPI indicators.
* Handling categorical variables such as capital city information.
* Exploratory data analysis to identify historical trends and patterns.

## Analytical Approach

### 1. ARIMA Time Series Forecasting

ARIMA (AutoRegressive Integrated Moving Average) was applied to analyse historical property price trends and forecast future price movements based on time-dependent patterns.

Key steps:

* Identified historical price trends.
* Analysed time series behaviour.
* Developed forecasts for future residential property prices.

### 2. Random Forest Regression

A Random Forest Regression model was developed to identify non-linear relationships between property prices and economic factors.

Model inputs included:

* City-level property prices.
* CPI as an economic predictor.
* Historical market trends.

## Model Evaluation

The predictive performance was evaluated using key regression metrics:

* Root Mean Square Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

The models were analysed to understand forecasting accuracy and identify the most reliable approach for predicting future property price growth.

## Results & Insights

* Identified potential future property growth patterns across Australian capital cities.
* Demonstrated the impact of inflation trends on residential property prices.
* Combined time series forecasting and machine learning techniques to improve predictive insights.
* Developed visual dashboards to communicate findings effectively.

## Data Visualization & Dashboard

An interactive Tableau dashboard was created to present:

* Historical property price trends.
* Forecasted growth patterns.
* Comparison between Australian capital cities.
* Key analytical insights.

## Tools & Technologies

* Python
* ARIMA Time Series Forecasting
* Random Forest Regression
* Tableau
* Exploratory
* Data Analysis
* Machine Learning
* Statistical Modelling

## Business Impact

This predictive analytics solution can support:

* Property investors in identifying potential growth markets.
* Businesses in strategic planning and market analysis.
* Policymakers in understanding housing market trends.
* Data-driven decision-making within the Australian property sector.

## Future Improvements

Future enhancements could include:

* Adding additional economic indicators such as interest rates, unemployment rates, and population growth.
* Applying advanced forecasting models such as XGBoost, Prophet, or LSTM neural networks.
* Improving model accuracy through hyperparameter tuning and feature engineering.

## Author

**Vimarsha Rathnayake**
Business Analytics | Data Analytics | Machine Learning | Business Intelligence
