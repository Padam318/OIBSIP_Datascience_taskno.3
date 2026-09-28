# OIBSIP_Datascience_taskno.3
# 🚗 Used Car Price Prediction

Predicting second-hand vehicle resale prices using Machine Learning in Python.

## 📌 Summary
* **Problem:** Estimate fair car resale values based on age, mileage, fuel type, and transmission.
* **Dataset:** Used car market data cleaned, preprocessed, and encoded.
* **Engineered Feature:** `Age_of_car = 2023 - Year` to capture vehicle depreciation.

## 🛠️ Tech Stack
`Python` • `Pandas` • `NumPy` • `Seaborn` • `Matplotlib` • `Scikit-Learn`

## 📊 Models & Performance
1. **Linear Regression (Baseline)**
2. **Random Forest Regressor (Tuned via `RandomizedSearchCV`)** ✨ *Best Model*

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | Low | Low | ~0.84 |
| **Random Forest (Tuned)** | **Lowest** | **Lowest** | **~0.90+** |

## 🚀 Quick Start
```bash
git clone [https://github.com/Padam318/car-price-prediction.git](https://github.com/Padam318/car-price-prediction.git)
pip install pandas numpy seaborn matplotlib scikit-learn
jupyter notebook
