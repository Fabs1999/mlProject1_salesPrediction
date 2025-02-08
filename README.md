# mlProject1_salesPrediction
🛒 Sales Forecasting with Upgini & CatBoost 🚀

This project is my first machine learning experiment, where I predict sales using Upgini for feature enrichment and CatBoost for regression modeling. The dataset includes historical sales data from 2013 to 2017, and the model is trained using time series techniques.

📌 Project Overview

Sales forecasting is a crucial task for businesses to optimize inventory and revenue. This project demonstrates how external feature enrichment and advanced machine learning models can improve sales prediction accuracy.

🔹 Key Features

📊 Sales Prediction: Forecasts future sales based on historical trends.

🚀 Feature Enrichment: Uses Upgini to add external features and improve model accuracy.

🤖 Machine Learning Model: Implements CatBoostRegressor for robust predictions.

📅 Time Series Data: Properly split into training (2013-2016) and testing (2017).

📂 Dataset

The dataset contains store-wise daily sales data.

Data is split into training (2013-2016) and testing (2017) based on date.

Features Used: Store ID, Item ID, Date, External Features (via Upgini).

🔮 Future Improvements

Improve feature selection and optimize hyperparameters.

Implement batch processing to handle Upgini API limits.

Deploy the model for real-time sales predictions.
