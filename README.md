# 🦠 COVID-19 Trend Analysis & Forecasting

> Time-series analysis & ARIMA forecasting on global COVID-19 data across 10 countries

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4C72B0?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

## 📌 Problem Statement
Analysing global COVID-19 trends to understand wave patterns and forecast near-term case trajectories using time-series modelling.

## 🎯 Key Results
| Metric | Result |
|--------|--------|
| Countries Analysed | **10** |
| Forecast Horizon | **30 days** |
| ARIMA MAPE | **< 8%** |
| Visualisations | **15+** |

## 📁 Project Structure
```
covid19-trend-analysis/
├── data/
│   └── covid_data.csv          # WHO open dataset (or synthetic)
├── notebooks/
│   ├── 01_Data_Exploration.ipynb   # EDA on global COVID data
│   └── 02_ARIMA_Forecasting.ipynb  # Time-series forecasting
├── requirements.txt
└── README.md
```

## 🔍 Key Analyses
- Daily/weekly case trend visualisation per country
- Wave detection and peak identification
- 30-day ARIMA forecast with confidence intervals
- Animated choropleth maps (Plotly) for global wave spread

## 🚀 How to Run
```bash
git clone https://github.com/VanilPatel/covid19-trend-analysis
cd covid19-trend-analysis
pip install -r requirements.txt
jupyter notebook notebooks/01_Data_Exploration.ipynb
```

## 🛠️ Tech Stack
- **Python** — Pandas, NumPy, Statsmodels (ARIMA), Scikit-learn
- **Visualisation** — Matplotlib, Seaborn, Plotly Express (choropleth)
- **Data Source** — WHO COVID-19 Dataset (public)

---
⭐ Star this repo if you found it helpful!
