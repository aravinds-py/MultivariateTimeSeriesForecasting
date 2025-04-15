# 📊 Multivariate Time Series Forecasting

This repository contains a Jupyter notebook focused on **Multivariate Time Series Forecasting**. The notebook demonstrates how to handle multiple time series data to predict future values by employing various forecasting models.

---

## 🔍 Overview

The project involves building forecasting models to predict future values of multiple related time series. Key components include:

- 🧹 Data preprocessing (cleaning, transformation, and scaling)
- ⚙️ Feature selection and engineering
- 🏗️ Model building (e.g., Linear Regression, LSTM, ARIMA, etc.)
- 📊 Model evaluation using various metrics (e.g., MAE, RMSE)
- 🔮 Forecasting future values

---

## 📁 Project Details

---

### 📑 Files

- **Multivariate Time Series Forecasting.ipynb**: The Jupyter notebook containing the analysis, model building, and forecasting.
- **stocks.csv**: Containing the dataset.

---

### 📊 Data

The dataset used in this notebook includes multiple time series data, which is loaded and processed for modeling. The data must be cleaned, normalized, and potentially feature-engineered to improve forecasting accuracy.

---

### 🤖 Models Used

1. **Linear Regression** 📉
2. **LSTM (Long Short-Term Memory)** 🧠
3. **ARIMA (AutoRegressive Integrated Moving Average)** 📈

---

### 📈 Evaluation Metrics

- **Mean Absolute Error (MAE)** 📏
- **Root Mean Squared Error (RMSE)** 📐

---

## 🚀 Getting Started

---

### 📜 Prerequisites

Make sure you have the following installed:

- Python 3.x 🐍
- Jupyter Notebook 💻
- Required libraries (listed below) 📚

---

## 📦 Libraries Used

- pandas 📊
- numpy ➗
- matplotlib 🎨
- scikit-learn 🧠
- tensorflow 🔥
- statsmodels 📉
- seaborn 🌊
- keras 🤖

---

## 🧠 Conclusion

LSTM is recommended for most complex time series forecasting tasks, especially those involving multiple related time series with intricate patterns. However, for more straightforward datasets with clear trends or stationarity, ARIMA could be a more computationally efficient choice. Linear Regression serves as a valuable starting point but should not be relied upon for accurate forecasting in complex time series scenarios.

---
