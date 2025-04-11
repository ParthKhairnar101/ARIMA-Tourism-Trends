# Foreign Tourist Arrival Forecasting using ARIMA/SARIMAX Models

## 📊 Overview
This project focuses on forecasting **Foreign Tourist Arrivals in India** using ARIMA and SARIMAX time series models. Given the limited real-world data (2014–2020), synthetic data augmentation was used to improve model performance and reduce underfitting.

## 🔍 Objectives
- Perform **Exploratory Data Analysis (EDA)** on tourism-related metrics.
- Implement and compare **ARIMA** and **SARIMAX** models for forecasting.
- Analyze model accuracy using MAE, MSE, RMSE, and MAPE.
- Explore the impact of synthetic data augmentation on forecasting accuracy.

## 📁 Project Structure
```plaintext
├── data/
│   └── tourism_data.csv              # Original dataset
├── notebook/
│   └── ARIMA_Tourism_Trends.ipynb       # Jupyter notebook with implementation
├── README.md                         # Project overview
```


## 🧪 Exploratory Data Analysis (EDA)
- Trends in annual foreign tourist arrivals.
- Country-wise origin of tourists (2014–2020).
- India's share in international tourist arrivals.
- Foreign exchange earnings from tourism (US$).
- Tourism receipts in international comparison.

## 🔧 Modeling Techniques
- **ARIMA** for univariate time series forecasting.
- **SARIMAX** to include exogenous variables (e.g., tourist origin countries).
- **Synthetic data generation** for years 2000–2013 and 2021–2024 to simulate realistic patterns.

## 📈 Model Evaluation
Metrics used:
- **MAE**
- **MSE**
- **RMSE**
- **MAPE**

Performance compared between:
1. Actual data model (2014–2020)
2. Synthetic augmented data model (2000–2024)

## 📊 Sample Output Table

| Model                        | MAE (M) | MSE (M²) | RMSE (M) | MAPE (%) |
|-----------------------------|---------|----------|----------|-----------|
| Actual Data (2014–2020)     |  X.XX   |   X.XX   |   X.XX   |   X.XX    |
| Synthetic Data (2000–2024)  |  X.XX   |   X.XX   |   X.XX   |   X.XX    |

## 📌 Key Findings
- Synthetic data significantly improves forecasting performance.
- SARIMAX allows inclusion of influencing variables.
- Forecasts from synthetic models show more realistic patterns and lower errors.

## 🔮 Future Enhancements
- Monthly or quarterly data for finer-grained predictions.
- Deep learning models (LSTM, GRU) for comparative analysis.
- Broader set of exogenous variables (GDP, policies, etc.).

## 🧠 Built With
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels

## 📬 Contact
For questions, feel free to reach out via the issues tab or connect on LinkedIn.

---
