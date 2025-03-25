# ML_Assignment_XGBOOST
XGBoost Salary Prediction

📌 Project Overview

This project demonstrates the use of XGBoost to predict salaries based on factors such as experience, education level, and job title.
The dataset is processed, trained using XGBoost, and evaluated for accuracy.



Xgb_Salary_Prediction.py - Main Python script to load data, train the model, and visualize feature importance.

Salary Data.csv - Sample dataset used for training and testing.

 How It Works

Load Data: Reads Salary Data.csv.

Preprocess Data: Encodes categorical variables (e.g., Education Level, Job Title).

Train Model: Uses XGBRegressor to learn salary patterns.

Evaluate Performance: Calculates RMSE to measure accuracy.

Visualize Feature Importance: Shows which factors impact salary the most.

 Model Performance

The model performance is evaluated using Root Mean Squared Error (RMSE). The lower the RMSE, the better the model's predictions.

 Future Improvements

Optimize hyperparameters for better accuracy.

Try different machine learning models (e.g., Random Forest, Neural Networks).

Use a larger dataset for better generalization.



