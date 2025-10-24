# Cryptocurrency-Forecasting
Time Series Forecasting

# Cryptocurrency Forecasting Using AI: A Deep Neural Network Model

This project implements a Deep Neural Network (DNN), likely an LSTM or GRU, to forecast the price of the Cardano (ADA) cryptocurrency. The model is built using TensorFlow and Keras, and the entire data-to-prediction pipeline is documented in the accompanying Jupyter Notebook and project report.

This repository is intended to demonstrate a complete data science workflow for time-series forecasting, including data preprocessing, feature engineering, model building, and evaluation.

## 🚀 Project Goal and Objectives

As outlined in the project report, the primary goal is to develop and evaluate a sophisticated AI model for cryptocurrency price prediction.

* **Objective 1:** To implement a Deep Neural Network model for time-series forecasting.
* **Objective 2:** To preprocess and prepare volatile cryptocurrency (Cardano) data for the model.
* **Objective 3:** To train and test the model on historical data to evaluate its predictive accuracy.
* **Objective 4:** To analyze the model's performance and its potential for practical financial forecasting.

## ✨ Methodology

1.  **Data Collection:** Used historical price data for Cardano (ADA).
2.  **Data Preprocessing:** The data was cleaned, normalized (e.g., using `MinMaxScaler`), and transformed into sequences suitable for a time-series model.
3.  **Model Architecture:** A Deep Neural Network (likely a Recurrent Neural Network like LSTM or GRU) was constructed using TensorFlow/Keras to capture temporal dependencies in the price data.
4.  **Training & Evaluation:** The model was trained on a set of historical data and then evaluated on a separate test set to measure its performance, culminating in a 15-day price forecast.

## 💻 Technology Stack

* **Core Libraries:** Python, Pandas, NumPy
* **Deep Learning:** TensorFlow, Keras
* **Data Visualization:** Matplotlib
* **Data Preprocessing:** Scikit-learn (for scaling)
* **Development:** Jupyter Notebook

---

## 🚀 How to Run This Project

### 1. Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)harishbalaji07/Cryptocurrency-Forecasting.git
cd Cryptocurrency-Forecasting
