# Airbnb Price Prediction (Machine Learning Project)

## 📌 Overview
This project builds a machine learning system to predict Airbnb listing prices based on historical data and listing features. The goal is to help hosts set optimal prices, improving revenue and booking rates.

## 🎯 Problem Statement
Airbnb hosts often struggle to decide the correct price for their listings. Incorrect pricing may lead to either loss of revenue or fewer bookings. This project develops regression models to estimate appropriate pricing automatically.

## ⚙️ Project Workflow
1. **Data Exploration & Cleaning**
   - Handled missing values, duplicates, and irrelevant columns.
   - Standardized data types and filled missing values using median/mode.
2. **Feature Engineering**
   - Created new features such as `host_exp_years` and `no_of_amenities`.
   - Applied transformations and one‑hot encoding for categorical variables.
3. **Model Building**
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
4. **Model Evaluation**
   - Metrics: RMSE, R²
   - XGBoost achieved the best performance (RMSE ≈ 0.394, R² ≈ 0.697).
5. **Visualization**
   - Heatmaps for missing values and correlations.
   - Distribution plots for log_price.

## 🛠️ Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit‑Learn, XGBoost, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook / Google Colab

## 📊 Results
- **XGBoost:** RMSE = 0.394, R² = 0.697 (best performance)
- **Random Forest:** RMSE = 0.412, R² = 0.669
- **Linear Regression:** RMSE = 0.651, R² = 0.650

## 📂 Repository Structure
## 📂 Dataset: [Google Drive Link](https://docs.google.com/spreadsheets/d/1hvXT6T2-AoQYMlmjvGRPa-3IXZ13XtyR/edit?usp=drive_link&ouid=105917977639559840330&rtpof=true&sd=true)
