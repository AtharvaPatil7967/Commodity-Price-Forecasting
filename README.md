# 📈 AgriPrice-Forecaster-ML: Agricultural Commodity Price Forecasting

This repository houses a comprehensive data science project focused on developing **high-accuracy predictive models for key agricultural commodity prices**. By analyzing historical market data and leveraging advanced machine learning algorithms, this system provides crucial forecasts for farmers, traders, and policymakers.

## 🎯 Project Goal

The primary objective is to accurately predict the daily and weekly **Modal Prices (Rs./kg)** for five major vegetables: **Tomato, Onion, Cabbage, Brinjal, and Potato** for the Pune market. The models are trained to achieve maximum accuracy (R² Score) and minimize prediction error (RMSE and MAPE).

## ✨ Key Features

* **Multi-Commodity Analysis:** Dedicated, highly-optimized models for **Tomato, Onion, Cabbage, Brinjal, and Potato**.
* **Advanced ML Pipeline:** Utilizes a full data science pipeline, including **Data Cleaning, Feature Engineering (Time-Series features), Robust Scaling, Time Series Cross-Validation, and Hyperparameter Tuning (GridSearch)**.
* **Model Comparison:** Benchmarks high-performance regression models like **Random Forest, Gradient Boosting, XGBoost, LightGBM, and CatBoost** to select the 'Best Model' for each commodity.
* **Performance Metrics:** Comprehensive evaluation using **R² Score, RMSE, MAE, and MAPE**. *All commodities achieved an R² score of 0.93 or higher.*
* **28-Day Forecasts:** Generates actionable 4-week forward-looking price predictions, including weekly average prices and trend analysis.

## 💻 Tech Stack

| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | Python |
| **Core Libraries** | `pandas`, `numpy`, `datetime` |
| **Machine Learning** | `scikit-learn`, `xgboost`, `lightgbm`, `catboost` |
| **Visualization** | `matplotlib`, `seaborn` (Presumed for dashboard generation) |

## 📁 Repository Structure Highlights

* `App.ipynb`: The main Jupyter Notebook containing the full ML pipeline from data ingestion to model training, evaluation, and forecasting.
* `FinaliseData.csv`: The cleaned and pre-processed historical price dataset.
* `Model_Performance_Results_20250731_150148.csv`: Detailed performance metrics for the best model selected for each commodity.
* `*_28Day_Predictions_*.csv`: Output files containing the 28-day price forecasts for each vegetable (e.g., `Onion_28Day_Predictions...`).
* `Model_Performance_Dashboard_...`: Visualizations summarizing the model performance and prediction analysis.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/AgriPrice-Forecaster-ML.git](https://github.com/YourUsername/AgriPrice-Forecaster-ML.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt # (Requires creating a requirements file)
    ```
3.  **Run the analysis:**
    Open and execute the cells in `App.ipynb`.
