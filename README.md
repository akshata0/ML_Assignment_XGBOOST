Rainfall Prediction using XGBoost

This project builds a machine learning model to predict rainfall using weather data and the powerful XGBoost algorithm. It demonstrates the full pipeline: from data preprocessing and visualization to model training and evaluation.

---

##  Project Structure

- `Rainfall_Xgb.ipynb` – Main Jupyter notebook with all code, training, evaluation, and plots.
- `README.md` – Project overview and setup instructions.

---

##  Problem Statement

The goal is to predict whether it will rain (`rainfall = 1`) or not (`rainfall = 0`) based on features like temperature, humidity, cloud cover, and wind.

---

##  Technologies Used

- **Python 3**
- **XGBoost**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**

---

## Model Summary

- Model: `XGBClassifier`
- Evaluation Metric: Accuracy, Confusion Matrix, and Classification Report
- Techniques used:
  - Train-test split
  - Hyperparameter tuning
  - Feature importance visualization

---

## Features Used

- Temperature (min, max, mean)
- Dew point
- Humidity
- Wind direction & speed
- Cloud cover
- Sunshine duration

---

📈 Results
✅ Baseline accuracy: ~86.8%

✅ Accuracy after tuning: ~88–89%
