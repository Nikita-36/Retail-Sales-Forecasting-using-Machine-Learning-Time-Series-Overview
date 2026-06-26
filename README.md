# Retail-Sales-Forecasting-using-Machine-Learning-Time-Series-Overview
Retail Sales Forecasting using Linear Regression, Random Forest, and ARIMA with Python, Scikit-learn, and Statsmodels.

# Retail Sales Forecasting using Machine Learning & Time Series

## Overview
This project forecasts retail sales using historical transaction data and machine learning techniques. It includes data preprocessing, time-series processing, feature engineering, model training, performance evaluation, and sales forecasting.

## Dataset
The dataset was obtained from Kaggle and contains retail transaction records with the following features:
* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

**Target Variable**
* Total Amount (Sales)

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Statsmodels
* Matplotlib

## Machine Learning Workflow
* Loaded and explored the dataset.
* Converted the Date column to datetime format and sorted transactions by date.
* Aggregated daily sales for time-series analysis.
* Engineered time-based features (Day, Month, Year, Day of Week).
* Trained Linear Regression and Random Forest Regression models.
* Built an ARIMA model for time-series forecasting.
* Evaluated model performance using Mean Absolute Error (MAE).
* Visualized actual versus predicted sales trends.
* Generated a 7-day sales forecast.

## Models Used
* Linear Regression
* Random Forest Regressor
* ARIMA

## Evaluation Metric
* Mean Absolute Error (MAE)

## Project Structure
Retail-Sales-Forecasting/
│── retail_sales_dataset.csv
│── retail_sales_forecasting.py
│── README.md

## Dataset Source
This project uses a dataset obtained from **Kaggle** for educational and machine learning practice purposes.

## Future Improvements
* Perform hyperparameter tuning for improved accuracy.
* Compare additional forecasting models.
* Build an interactive dashboard using Streamlit.
* Deploy the forecasting model for real-time sales prediction.

