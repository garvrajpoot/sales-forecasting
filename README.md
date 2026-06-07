# 📈 Sales Forecasting

Predicting monthly revenue using historical sales data to help businesses
plan inventory, staffing, and budgets with confidence.

---

## 📌 Problem Statement
Businesses make critical decisions based on expected revenue. This project
builds a time series forecasting model that predicts future monthly sales
using historical trends and seasonality patterns.

---

## 📊 Dataset
- **Source:** [Superstore Sales — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Size:** 9,994 orders across 4 years
- **Target Variable:** Monthly Sales ($)

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Statsmodels (Holt-Winters Exponential Smoothing)
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🔄 Project Workflow
1. Load & explore the data
2. Clean & aggregate into monthly totals
3. Visualize sales trend & seasonality
4. Train Holt-Winters forecasting model
5. Evaluate & visualize forecast vs actual

---

## 📈 Results
| Metric | Score |
|--------|-------|
| MAE | $12,931.85 |
| RMSE | $17,768.85 |

---

## 💡 Key Business Insights
- Sales show a clear upward trend over the observed period
- Strong Q4 seasonality detected every year
- Model forecasts can directly inform inventory and staffing decisions

---

## 🚀 How to Run
1. Clone the repo
2. Download the dataset from Kaggle and place it in the project folder
3. Open `Sales-Forecasting.ipynb` in Jupyter Notebook
4. Run all cells in order

---

## 📁 File Structure
