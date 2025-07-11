# 🧪 Silica Percentage Prediction in Froth Flotation | ML Regression Project

Predicting silica content in iron ore using process parameters from the froth flotation stage, leveraging machine learning models to support quality control in mineral processing. This project applies machine learning to predict the percentage of silica (%SiO₂) in the froth flotation process of iron ore beneficiation. Froth flotation is a crucial step in improving ore quality by removing impurities like silica.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Future Work](#future-work)
- [License](#license)

---

## 📘 Overview

This project uses machine learning to predict the **percentage of silica (%SiO₂)** present in the output of the froth flotation process—a critical step in iron ore beneficiation. Accurate prediction of silica levels can significantly improve operational efficiency and product quality in mineral processing plants.

The goal is to build robust regression models that estimate silica content using features such as:
- Pulp density
- Reagent dosages
- Slurry pH
- Air flow rate
- Feed rate

---

## 📊 Dataset

The dataset contains process variables collected during the froth flotation operation. Each record includes:

- Input process parameters (numerical)
- Target variable: **Silica content (%)**



## 🧠 Methodology

1. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Pair plots and distribution curves

2. **Preprocessing**
   - Handling missing values
   - Feature scaling using `StandardScaler`

3. **Model Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - XGBoost Regressor

4. **Model Evaluation**
   - Metrics: R² Score, MAE, RMSE
   - Cross-validation
   - Residual analysis

5. **Best Model**
   - **XGBoost Regressor** selected as the final model based on performance

---

## ✅ Results

- **XGBoost Regressor**
  - R² Score: *~0.95*
  - RMSE: *~0.25*

📉 Prediction vs. Actual plots and feature importance graphs are included in the notebook.


