# Cryptocurrency Market Analysis & Prediction (Machine Learning)

## Project Overview
This project focuses on analyzing and predicting cryptocurrency market behavior using Machine Learning techniques.

It aims to support investment decision-making, risk management, and market understanding through data-driven insights.

---

## Business Objectives

### BO1: Optimize Investment Strategy

#### DSO1 – Regression
Predict the future price of a cryptocurrency based on historical data.

- Target (quantitative): price_usd  
- Features: price_usd, chg_24h, chg_7d, vol_24h, market_cap  

#### DSO2 – Classification
Predict whether the price will go up or down in the next timestamp.

- Target (qualitative):
  - chg_24h > 0 → Increase  
  - chg_24h <= 0 → Decrease  

---

### BO2: Portfolio Diversification

#### DSO3 – Clustering
Group cryptocurrencies based on market behavior.

- Features: price_usd, vol_24h, chg_24h, chg_7d, market_cap  
- Methods:
  - K-Means  
  - Hierarchical Clustering  

---

### BO3: Market Understanding & Correlation Analysis

#### DSO4 – Exploratory Data Analysis (EDA)

- Analyze relationships between variables:
  - market_cap vs price_usd  
  - vol_24h vs chg_24h  
- Identify dominant cryptocurrencies in the market  

- Methods:
  - Scatter plots  
  - Correlation heatmaps  

---

### BO4: Risk Management & Portfolio Optimization

#### DSO5 – Quantitative Risk Analysis

- Estimate volatility of each cryptocurrency  
- Identify high-risk vs low-risk assets  

- Methods:
  - Standard deviation  
  - Min/Max analysis  
  - Moving averages  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Project Structure

data/         → datasets  
notebooks/    → experiments and analysis  
src/          → machine learning pipeline  
models/       → trained models  
results/      → visualizations and metrics  

---

## How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Run the project:
python main.py

3. Open notebooks:
jupyter notebook

---

## Key Outcomes

- Price prediction model (regression)  
- Trend classification model (up/down)  
- Cryptocurrency clustering  
- Market insights through exploratory analysis  
- Risk evaluation metrics  

---

## Use Cases

- Investment decision support  
- Portfolio diversification  
- Risk analysis in crypto markets  
- Financial data analysis  

---



---

## Notes

- Dataset includes historical cryptocurrency data  
- Visualizations available in the results folder  
