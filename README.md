# 🚖 Uber Fare Prediction (Regression)

## 📌 Project Overview
This project predicts Uber taxi fare prices using machine learning regression models based on trip details such as pickup location, drop location, passenger count, and trip distance.

## 📊 Dataset
Dataset used: Uber Fares Dataset

Source: https://www.kaggle.com/datasets/yasserh/uber-fares-dataset

### Features
- Pickup Latitude
- Pickup Longitude
- Dropoff Latitude
- Dropoff Longitude
- Passenger Count
- Pickup Datetime
- Fare Amount

## ⚙️ Feature Engineering
The distance between pickup and drop locations is calculated using the **Haversine Distance Formula**.

## 🤖 Machine Learning Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 📏 Evaluation Metrics
The models are evaluated using:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

## 📂 Project Files
- `uber.csv` → Dataset
- `uber.ipynb` → Machine Learning Notebook
- `README.md` → Project Documentation

## 🎯 Conclusion
This project demonstrates how machine learning models can predict taxi fares based on trip details. Feature engineering such as distance calculation improves prediction accuracy.
