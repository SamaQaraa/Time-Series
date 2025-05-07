# 🕒 Time Series Forecasting Assignments

This repository contains five structured time series assignments focused on applying various forecasting techniques ranging from classical statistical models to machine learning approaches using the **hhblock dataset** .

---

## 📚 Task Breakdown

### 🔹 Task 1: Visualization & Decomposition

- **Dataset**: `hhblock` folder
- **Steps**:
  1. Choose any block file and a specific `LCLid` (consumer).
  2. Plot:
     - Line plot
     - Seasonal plot
     - Heatmap
  3. Apply Time Series Decomposition (trend, seasonality, residual).

---

### 🔹 Task 2: ETS Models & Stationarity Testing

- **Dataset**: `hhblock` folder
- **Steps**:
  1. Test for stationarity (hourly, daily, weekly, monthly) using ADF or KPSS tests.
  2. Forecast using ETS (Exponential Smoothing) models.
  3. Add markdown explanations and useful insights.

---

### 🔹 Task 3: ARIMA Family – Box-Jenkins Approach

- **Dataset**: `hhblock` folder
- **Steps**:
  1. Apply ARIMA, SARIMA, and AutoARIMA models.
  2. Diagnose models with ACF/PACF plots.
- **Deliverables**:
  - Comparative plots for all models.
  - Markdown explanations & diagnostic interpretations.

---

### 🔹 Task 4: Forecasting with Prophet

- **Dataset**: `hhblock` folder
- **Steps**:
  1. Fit and tune the Prophet model to the dataset.
  2. Experiment with optimal changepoints, seasonality, and parameter tuning.
  3. Provide markdown analysis of forecasts.
- **Deliverables**:
  - Include tuning parameter thought process.

---

### 🔹 Task 5: Machine Learning Forecasting (Random Forest)

- **Dataset**: `hhblock` folder
- **Objective**:
  1. Build ML forecasting model using Random Forest (no bootstrapping).
  2. Experiment with:
      - Time-delay embeddings
      - Temporal embeddings
      - Combined embeddings effect
  3. Evaluate performance at hourly, daily, weekly, and monthly forecasts.

---


## 📦 Folder Structure

    TIME-SERIES/
    │
    ├── Task1/
    │ └── Visualization_Decomposition.ipynb
    │
    ├── Task2/
    │ └── Stationarity_ETS.ipynb
    │
    ├── Task3/
    │ └── BoxJenkins_ARIMA.ipynb
    │
    ├── Task4/
    │ └── Prophet_Modeling.ipynb
    │
    ├── Task5/
    │ ├── Daily_Task5.ipynb
    │ ├── Hourly_Task5.ipynb
    │ ├── Monthly_Task5.ipynb
    │ └── Weekly_Task5.ipynb
    │
    └── README.md


