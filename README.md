🚖 Uber Fare Prediction System
📌 Overview
The Uber Fare Prediction System is a machine learning project that predicts the fare amount of future rides using regression analysis on historical Uber trip data. The model analyzes key features such as distance, time, and pickup/drop-off locations to estimate ride prices accurately.
🎯 Objective
To develop a regression-based machine learning model that can predict future ride fares and help users make informed travel decisions.
🚀 Features
Predicts Uber ride fares using historical data
Handles missing and noisy real-world data
Performs feature engineering (distance, datetime, etc.)
Uses multiple regression models for comparison
Evaluates model performance using standard metrics
🛠️ Tech Stack
Python
Pandas, NumPy – Data preprocessing
Matplotlib, Seaborn – Data visualization
Scikit-learn – Machine learning models
Jupyter Notebook
📊 Dataset
Uber ride dataset containing:
Pickup & drop-off coordinates
Date & time of ride
Fare amount
(You can add dataset link here if from Kaggle)
⚙️ Workflow
Data Collection
Data Cleaning & Handling Missing Values
Exploratory Data Analysis (EDA)
Feature Engineering
Distance calculation (Haversine Formula)
Extracting time-based features (hour, day, etc.)
Model Training (Regression Models)
Model Evaluation
Fare Prediction
📈 Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor
📉 Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
📊 Results
The model achieved good prediction performance after applying feature engineering and model tuning. Random Forest performed better compared to other models in terms of accuracy
