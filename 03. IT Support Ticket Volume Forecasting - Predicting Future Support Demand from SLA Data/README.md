# IT Support Ticket Volume Forecasting

Project portfolio Data Analyst / Data Science menggunakan data SLA Support 2025–2026.

## Objective
Forecast jumlah tiket IT Support per hari untuk membantu:
- capacity planning,
- workload planning,
- staffing,
- SLA monitoring.

## Dataset
- SLA Support Full Year 2025
- SLA Support Full Year 2026

Periode 2026 bersifat year-to-date sehingga Oktober 2026 belum lengkap.

## Method
1. Data loading
2. Data cleaning
3. Daily time-series aggregation
4. EDA
5. Time-based train/test split
6. Baseline comparison
7. Holt-Winters
8. Random Forest dengan lag features
9. Model evaluation
10. 30-day future forecast
11. Business interpretation

## Evaluation
Metrics:
- MAE
- RMSE
- MAPE

September 2026 digunakan sebagai holdout period agar evaluasi tidak mengalami data leakage.

## Tools
Python, Pandas, Matplotlib, Scikit-learn, Statsmodels, Google Colab.

## Portfolio Title
**IT Support Ticket Volume Forecasting — Predicting Future Support Demand from SLA Data**

## Business Value
Forecast membantu tim support mengantisipasi demand, mengatur kapasitas, dan menghubungkan workload dengan SLA performance.

## Files
- `IT Support Response Time Prediction Using using XGBoost Regressor.ipynb`
