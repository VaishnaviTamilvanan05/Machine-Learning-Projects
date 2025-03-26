# 🚴‍♂️ Bike Rental Demand Prediction

## 📜 Project Overview
In this project, we tackle the challenge of predicting bike rental demand for a city-wide bike-sharing system. Using historical data, we aim to forecast the number of bikes rented at specific hours throughout the day. This is crucial for optimizing bike availability and ensuring a smooth user experience. 

This project was inspired by the [Kaggle Bike Sharing Demand competition](https://www.kaggle.com/c/bike-sharing-demand), where participants are tasked with building models that minimize forecasting errors.

## 🔍 Problem Statement
How can we predict the demand for bike rentals, given factors like weather conditions, time, and seasonal variations? By answering this, bike-sharing systems can efficiently allocate resources and reduce customer wait times.

## 🚀 Approach
We implemented and fine-tuned three powerful machine learning models to predict bike rental counts:

- **Random Forest** 🌲: A robust ensemble model known for handling large datasets.
- **XGBoost** 🚀: A high-performance gradient boosting framework that gave the best results.
- **CatBoost** 🐱: Another gradient boosting model designed to handle categorical features.

## ⚙️ Key Steps
1. **Data Preprocessing**: We cleaned the data, engineered new features, and normalized inputs for better model performance.
2. **Model Training**: All three models were trained on the data, with careful hyperparameter tuning to improve prediction accuracy.
3. **Evaluation**: The models were evaluated based on the Root Mean Squared Logarithmic Error (RMSLE), the competition's scoring metric.
4. **Hyperparameter Optimization**: Using grid search and cross-validation, we tuned the models to minimize the RMSLE.
5. **Final Selection**: After comparing performance, **XGBoost** came out on top with the lowest RMSLE, making it our go-to model for generating predictions.

## 🔑 Results
- **XGBoost** emerged as the top performer, providing the most accurate forecasts for bike rentals.
- The final predictions were submitted in a CSV format, ready for evaluation on Kaggle.

## 💡 Conclusion
This project highlights the power of gradient boosting models like XGBoost in making accurate predictions for time-series data. By carefully preprocessing data and optimizing model parameters, we managed to predict bike rental demand with high precision.

## 📁 Project Structure
- `datasets_project/`: Contains the training and test datasets.
- `Utilities/`: Includes the Jupyter notebooks with shallow models and some common functions used in PMLM.
- `result/submission/`: The final CSV file with predictions.

