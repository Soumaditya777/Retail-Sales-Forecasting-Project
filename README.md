# 🛍️ Retail Sales Forecasting

Forecasting retail sales using historical data and machine learning techniques.  
This project compares daily vs. weekly sales forecasting to understand how resampling can improve forecast accuracy, trend visibility, and seasonal pattern detection.

---

## 📁 Files

- `Retail_Sales_Forecasting.ipynb`: Main Jupyter notebook with full EDA, modeling, and forecasting
- `sales_data.csv`: Input dataset containing daily sales records

---

## 🎯 Objective

Build predictive models that forecast future sales, helping retailers make informed decisions about inventory, marketing, and logistics.

---

## 🧰 Tools & Libraries

- **Pandas**: Data manipulation, resampling
- **Matplotlib / Seaborn**: Visualization
- **XGBoost**: ML-based forecasting model
- **scikit-learn**: Metrics and model evaluation

---

## 🧠 Key Concepts

- Time Series Resampling (daily → weekly)
- Trend & Seasonality Detection
- Regression Modeling on Time Series
- RMSE as Evaluation Metric
- Visual Forecast Comparison

---

## 📊 Forecasting Methods Compared

### 🔹 Daily Forecast
- Hard to capture trend/seasonality
- Looks flat or inconsistent
- Lower RMSE (~100) due to small values

### 🔹 Weekly Forecast
- Clearer patterns and seasonality
- Realistic and interpretable trends
- Higher RMSE (~600), but better planning value

---

## 📌 Results Summary

| Granularity | RMSE  | Trend & Seasonality | Business Value |
|-------------|-------|---------------------|----------------|
| Daily       | ~100  | Poor                | Low            |
| Weekly      | ~600  | Good                | High           |

> Weekly forecasting captures long-term patterns better and provides more useful insights for real-world retail decision-making.

---

## 🚀 Run It Yourself

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/retail-sales-forecasting.git
   cd retail-sales-forecasting
