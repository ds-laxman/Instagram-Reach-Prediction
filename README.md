# 📈 Instagram Reach Forecasting with SARIMA

Forecast future Instagram reach using time series analysis with the SARIMA model.

---

## 📖 Overview

This project focuses on forecasting Instagram reach over time by applying the SARIMA (Seasonal AutoRegressive Integrated Moving Average) model. By analyzing temporal patterns in the data, we aim to provide accurate predictions of future reach, aiding in strategic content planning.

---

## 🎯 Project Objectives

- Analyze historical Instagram reach data to identify trends and seasonal patterns.
- Develop a SARIMA-based model to forecast future reach.
- Evaluate the model's performance and refine it for improved accuracy.

---

## 🗂 Dataset

- **Source**: [Kaggle - Instagram Reach Dataset](https://www.kaggle.com/datasets/rahulchavan99/instagram-reach-forecasting)  
- **Structure**:
  - `Date`: Timestamps of Instagram posts.
  - `Reach`: Number of users reached on each date.
- **Preprocessing**:
  - Converted `Date` column to datetime format.
  - Set `Date` as the index for time series analysis.
  - Checked for and handled missing values.

---

## 🛠 Technologies Used

- **Programming Language**: Python 3.8
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Time Series Analysis: `statsmodels`
- **Environment**: Google Colab

---

