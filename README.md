# Maritime Demand & Supply Forecasting

This repository contains my MSc capstone project focused on forecasting
maritime demand and supply using statistical, machine learning, and deep
learning approaches.

---

## Project Overview
The objective of this project is to analyze global and regional maritime
trade data and build forecasting models that support strategic
decision-making in the shipping and logistics sector.

The project compares traditional time-series models with advanced
machine learning and deep learning techniques to evaluate their
performance under different data conditions.

---

## Data
- Source: UNCTAD (United Nations Conference on Trade and Development)
- Scope:
  - Global maritime demand and supply
  - Saudi Arabia case study
- Metrics:
  - Seaborne trade volumes
  - Merchant fleet capacity (DWT)

⚠️ **Note:**  
The dataset is not included in this repository due to licensing and usage
restrictions.

---

## Methodology
The project follows a structured analytical workflow:

1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Time-series modeling  
4. Machine learning and deep learning modeling  
5. Model evaluation and comparison  
6. Explainable AI (XAI) analysis  

---

## Models Used
- **ARIMA** – Statistical time-series forecasting (baseline model)
- **XGBoost** – Machine learning regression for supply forecasting
- **LSTM** – Deep learning model for complex temporal patterns
- **Explainable AI (XAI)** – Model interpretation and transparency

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Statsmodels  
- Scikit-learn  
- XGBoost  
- TensorFlow / Keras  
- SHAP (Explainable AI)  
- Jupyter Notebook  

---

## Repository Structure
maritime-demand-supply-forecasting/
├── notebooks/ # Jupyter notebooks for modeling and experiments
│ ├── ARIMA models
│ ├── XGBoost models
│ └── LSTM models
├── docs/ # Research paper and supporting documents
├── LICENSE
└── README.md



---

## Key Findings
- ARIMA performs robustly on limited and short historical data.
- Machine learning and deep learning models demonstrate improved
  performance when longer and richer time series are available.
- Explainable AI enhances transparency and trust in forecasting results.



---

## Author
**Lama Turki**  
MSc Data Science & Analytics  
