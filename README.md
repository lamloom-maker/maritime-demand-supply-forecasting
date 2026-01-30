Maritime Demand & Supply Forecasting

This repository contains my MSc capstone project focused on forecasting maritime demand and supply using statistical, machine learning, and deep learning approaches, with an emphasis on explainability and real-world decision support.

Project Overview

Maritime trade plays a critical role in the global economy, carrying more than 80% of world trade volumes. Accurate forecasting of maritime demand and supply is essential for strategic planning, capacity management, and policy-making in the shipping and logistics sector.

This project aims to develop and compare forecasting models for maritime demand and supply at both global and regional (Saudi Arabia) levels, using time-series, machine learning, and deep learning techniques.

Objectives

Analyze long-term maritime trade and fleet capacity trends

Build robust forecasting models under different data conditions

Compare classical statistical models with advanced ML and DL approaches

Apply Explainable AI (XAI) techniques to improve model transparency

Support data-driven decision-making for policymakers and industry stakeholders

Data

Source:
United Nations Conference on Trade and Development (UNCTAD)

Scope:

Global maritime demand and supply

Saudi Arabia case study

Key Metrics:

Seaborne trade volumes

Merchant fleet capacity (DWT – Deadweight Tonnage)

⚠️ Note:
The dataset is not included in this repository due to licensing and usage restrictions.

Methodology

The project follows a structured and reproducible analytical workflow:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Time-series modeling

Machine learning and deep learning modeling

Model evaluation and comparison

Explainable AI (XAI) analysis

All models are evaluated using time-based splits to preserve temporal integrity.

Models Used
ARIMA (Statistical Forecasting)

Baseline time-series model

Strong performance on limited historical data

High interpretability

XGBoost (Machine Learning)

Regression-based forecasting for supply and demand

Feature engineering using lagged variables and trend components

Improved performance with richer datasets

LSTM (Deep Learning)

Captures complex temporal dependencies

Suitable for long-term and nonlinear patterns

Applied to extended time-series horizons

Explainable AI (XAI)

Residual diagnostics for ARIMA

SHAP-based explanations for XGBoost

Improves transparency and trust in model outputs

Key Findings

ARIMA performs robustly on short and limited datasets

Machine learning and deep learning models outperform classical methods when longer historical data is available

Explainable AI enhances interpretability and supports responsible AI deployment

No single model fits all scenarios — model selection depends on data availability and use case

Tools & Technologies

Python

Pandas, NumPy

Statsmodels

Scikit-learn

XGBoost

TensorFlow / Keras

SHAP (Explainable AI)

Jupyter Notebook

Repository Structure
maritime-demand-supply-forecasting/
│
├── notebooks/          # Modeling and experimentation notebooks
│   ├── ARIMA models
│   ├── XGBoost models
│   └── LSTM models
│
├── docs/               # Research paper and supporting documents
│
├── LICENSE
└── README.md

Applications

Maritime policy and planning

Port capacity forecasting

Shipping market analysis

Strategic logistics decision-making

Explainable AI in time-series forecasting

Author

Lama Turki
MSc Data Science & Analytics
Data Scientist | Analytics & Forecasting
