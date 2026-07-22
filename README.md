# 🛒 Retail Demand Forecasting using Machine Learning & Time Series Analysis

## 📌 Project Overview

This project develops an end-to-end **Retail Demand Forecasting** solution using historical e-commerce sales data. The objective is to accurately predict future product demand to support **inventory optimization, demand planning, and business decision-making**.

The project combines **Machine Learning** and **Classical Time Series Forecasting** techniques to compare different approaches and identify the most effective forecasting model.

---

# 🎯 Business Problem

Retail businesses often struggle to maintain optimal inventory levels due to uncertain customer demand.

Poor demand forecasting can lead to:

* Overstocking
* Stockouts
* Increased inventory costs
* Lost sales
* Poor customer satisfaction

This project aims to build an intelligent forecasting system capable of predicting future product demand using historical sales data.

---

# 📂 Dataset

**Dataset:** Olist Brazilian E-Commerce Dataset

The project integrates multiple datasets, including:

* Customers
* Orders
* Order Items
* Products
* Product Categories
* Payments
* Reviews

After preprocessing, a daily category-level demand dataset was created for forecasting.

---

# ⚙️ Project Workflow

### 1. Data Collection

* Imported multiple Olist datasets
* Explored data structure
* Performed initial validation

### 2. Data Cleaning

* Missing value treatment
* Duplicate removal
* Datetime conversion
* Feature validation

### 3. Data Integration

* Merged multiple datasets
* Created a master analytical dataset

### 4. Exploratory Data Analysis (EDA)

* Sales trends
* Category analysis
* Customer behavior
* Demand distribution
* Correlation analysis

### 5. Feature Engineering

Created forecasting features including:

* Lag Features
* Rolling Mean
* Rolling Standard Deviation
* Exponential Moving Average (EMA)
* Calendar Features
* Cyclical Features
* Category Encoding

### 6. Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor
* LightGBM Regressor
* CatBoost Regressor

### 7. Classical Time Series Models

* ARIMA
* SARIMA
* Prophet

### 8. Model Evaluation

Models were evaluated using:

* MAE
* RMSE
* R² Score
* MAPE
* WAPE

### 9. Future Forecasting

Generated a **30-day demand forecast** using the best-performing classical forecasting model.

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Statsmodels
* XGBoost
* LightGBM
* CatBoost
* Prophet

### Development Environment

* Jupyter Notebook
* Anaconda

---

# 📊 Machine Learning Models

* Linear Regression
* Decision Tree
* Random Forest
* XGBoost
* LightGBM
* CatBoost

---

# 📈 Time Series Models

* ARIMA
* SARIMA
* Prophet

---

# 📏 Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score
* Mean Absolute Percentage Error (MAPE)
* Weighted Absolute Percentage Error (WAPE)

---

# 💼 Business Impact

The forecasting solution can help retailers:

* Improve inventory planning
* Reduce stockouts
* Minimize excess inventory
* Optimize procurement planning
* Improve warehouse utilization
* Support data-driven business decisions

---

# 🚀 Future Improvements

* Hyperparameter tuning using Optuna or GridSearchCV
* Deep Learning forecasting (LSTM, TFT, N-BEATS)
* Holiday and promotion features
* Automated model retraining
* Real-time forecasting pipeline
* Streamlit dashboard deployment

---

# 📁 Repository Structure

```
Retail-Demand-Forecasting/
│
├── data/
├── notebooks/
├── images/
├── models/
├── outputs/
├── Retail_Demand_Forecasting.ipynb
├── README.md
└── requirements.txt
```

---

# 👨‍💻 Author

**Amol Dangat**

Data Scientist | Machine Learning | Time Series Forecasting | Predictive Analytics

If you found this project useful, feel free to ⭐ the repository and connect with me on LinkedIn.
