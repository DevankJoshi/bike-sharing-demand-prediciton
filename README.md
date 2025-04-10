# 🚴‍♂️ Bike Sharing Demand Prediction

This repository contains a Python script to forecast the **bike-sharing demand** using historical usage data. The goal is to build a regression model that predicts the number of rental bikes required for a particular time period, helping optimize fleet management and resource planning.

---

## 📘 Project Overview

The script `bikes_sharing_demand.py` covers the full machine learning pipeline:

- 📥 Importing and preprocessing bike usage data
- 📊 Exploratory Data Analysis (EDA)
- 🧠 Feature engineering and selection
- 🧪 Training regression models (e.g., Linear Regression, Random Forest, etc.)
- 📈 Evaluating model performance using MAE, RMSE, and R²
- 💾 Option to export results or save the trained model

---

## 📂 Dataset

**Filename**: `BoomBike.csv`

This dataset contains hourly bike rental information, with features such as:

- `datetime`
- `season`
- `holiday`
- `workingday`
- `weather`
- `temp`, `atemp`, `humidity`, `windspeed`
- `casual`, `registered`, `count`

Ensure this file is in the same directory as the Python script before running.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---
