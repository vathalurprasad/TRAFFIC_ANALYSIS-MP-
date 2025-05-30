# TRAFFIC_ANALYSIS-MP-
# Traffic Volume Prediction using Machine Learning

This project aims to predict hourly traffic volume using machine learning techniques. It uses historical data along with weather, holiday, and event data to improve prediction accuracy.

# Problem Statement

The goal is to predict future traffic volume to help with traffic congestion planning, optimization of signals, and event-based control using historical data.

# Tools & Technologies

- Python
- Pandas, NumPy
- XGBoost Regressor
- Matplotlib, Seaborn
- Scikit-learn

# Features & Techniques

- Time-based feature engineering (`hour`, `day_of_week`, `month`)
- Lag features and rolling means
- One-hot encoding of categorical variables (`weather`, `event`)
- XGBoost for regression
- Model evaluation using MAE, RMSE, and R² score
- Visualization of predictions and feature importance

# Dataset

Includes fields like:
- `timestamp`, `traffic_volume`, `temperature`
- `weather`, `event`, `is_holiday`, `incident`

#  Model Results

- **MAE:** 63.07
- **RMSE:** 78.55
- **R² Score:**  -0.03

#  Visualizations

- Actual vs Predicted Traffic Volume
- Feature Importance Graph

#  Future Enhancements

- Integrate real-time data and prediction dashboard
- Experiment with LSTM for sequential modeling
- Include more granular location and camera data



