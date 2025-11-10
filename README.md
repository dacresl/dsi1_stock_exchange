# dsi1_stock_exchange

# 📈 Predicting Stock Index Closing Prices

## 👥 Members

- Fay Kisteroff  
- Olena Peleshko  
- Nneka Asuzu  
- Deanne Acres-Lans  
- Ruchira Malhotra  

---

## 🧠 Project Overview

**Source:** [Kaggle – Stock Exchange Data](https://www.kaggle.com/)

Stock market movements are influenced by various factors, and predicting short-term changes is a challenging yet valuable task for investors and analysts. Accurate predictions can help in making informed trading decisions and managing risk.

This project addresses the problem of predicting the direction of the next day's closing price using historical data.

### 🎯 Goal

To use moving average (MA) and volume as predictors of stock price movement, and analyze how these indicators behave in the context of broader market volatility (e.g., the COVID-19 pandemic).

### 📊 Features Used

- **Index**
- **Date**
- **10-day MA**: Indicator for short-term volatility/price changes  
- **21-day MA**: Reflects longer-term trends  
- **Volume**: Reflects market participation and sentiment; high volume can indicate volatility  

### 🏛️ Selected Indexes

- **NYA** – NYSE (USA)  
- **IXIC** – NASDAQ (USA)  
- **GSPTSE** – TSX (Canada)  

### 🕰️ Timeframes Compared

- **Pre-COVID:** Mar 2019 – Feb 2020  
- **Post-COVID:** Mar 2020 – May 2021  

---

## 🔬 Methodology

1. Clean and filter data  
2. Remove missing values  
3. Ensure date continuity (account for market closures)  
4. Filter for selected indexes  
5. Calculate 10-day and 21-day MAs per index  
6. Split data into train/test sets (chronological order preserved)  
7. Use 5-fold time-series cross-validation (rolling window)  
8. Train logistic regression models:  
   - **Model 1:** 10-day MA + Volume  
   - **Model 2:** 21-day MA + Volume  
9. Standardize volume and MA features  
10. Evaluate using AUC curves and confusion matrices  

---

## 🛠️ Technical Stack

- **Language:** Python  
- **Libraries:**
  - `numpy`: matrix operations  
  - `pandas`: data analysis  
  - `matplotlib`: graphs and plots  
  - `seaborn`: enhanced visualizations  
  - `sklearn`: model training and AUC ROC visualization
  - `kagglehub`: interaction with Kaggle data sets

---

## 📌 Project Scope

Develop a classification model to determine whether the 10-day or 21-day MA combined with trading volume is a better predictor of stock price movement. The project includes:

- Data preprocessing  
- Model training  
- Evaluation  
- Visualization  
- Insights and recommendations  

### 👥 Stakeholders

- Investors  
- Financial institutions  

---

## 🧹 Data Cleaning

- **Objective:**  
  *(To be completed)*

- **Method:**  
  *(To be completed)*

- **Results:**  
  *(To be completed)*

---

## 📈 Exploratory Analysis

- **Objective:**  
  *(To be completed)*

- **Method:**  
  *(To be completed)*

- **Results:**  
  *(To be completed)*

---

## 📉 Regression Analysis and Validation

- **Objective:**  
  *(To be completed)*

- **Method:**  
  *(To be completed)*

- **Results:**  
  *(To be completed)*

---

## ✅ Conclusion

*(To be completed)*

---

## 🔗 Team Member Links

| Name              | Links |
|-------------------|-------|
| Fay Kisteroff     |       |
| Olena Peleshko    |       |
| Nneka Asuzu       |       |
| Deanne Acres-Lans |       |
| Ruchira Malhotra  |       |
