# Data-Driven-Inventory-Optimization-via-Time-Series-Analysis

The goal of this project was to optimize inventory levels in service centers by leveraging time series analysis for accurate demand forecasting of spare parts. This approach helped reduce inventory costs and improve spare parts availability, ultimately enhancing customer satisfaction through efficient resource management.

Contents 📚
Import Stuff: Setting up the necessary libraries and tools.
Load the Data: Loading the dataset for analysis.
Basic EDA: Conducting initial exploratory data analysis to understand the dataset.
Data Preprocessing: Cleaning and preparing the data for time series analysis.
Advanced EDA: Diving deeper into the data to uncover patterns and insights.
Time Series Analysis: Analyzing the data to identify trends, seasonality, and other components.
Time Series Forecasting: Predicting future demand for spare parts using various time series models.
Model Evaluation: Assessing the performance of deployed models.
Multivariate Analysis: Enhancing the SARIMAX model by incorporating additional variables.
Features in Data 🔍
The dataset includes the following features, which are crucial for analysis and forecasting:

invoice_date
job_card_date
business_partner_name
vehicle_no
vehicle_model
current_km_reading
invoice_line_text
Models Deployed 🤖
To address the forecasting challenge, the following models were deployed:

Auto Regression (AR)
Moving Average (MA)
Exponential Weighted Moving Average (EWMA)
Holt-Winters Method
Seasonal Autoregressive Integrated Moving Average (SARIMA)
Seasonal Autoregressive Integrated Moving Average with Exogenous variables (SARIMAX)
Model Evaluation 📏
The models were evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
This project demonstrates the power of time series analysis and forecasting in solving real-world inventory management challenges. By predicting demand more accurately, service centers can optimize their inventory levels, reduce costs, and ensure the availability of spare parts, ultimately leading to greater customer satisfaction.
