# 🚀 Banking Stock Price Prediction Using Machine Learning & Deep Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge\&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge\&logo=tensorflow)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-MachineLearning-f7931e?style=for-the-badge\&logo=scikitlearn)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge\&logo=googlecolab)
![Status](https://img.shields.io/badge/Research-Completed-success?style=for-the-badge)

### 📊 Comparative Analysis of Machine Learning and Deep Learning Models for Banking Stock Forecasting

</div>

---

## 🌟 Project Overview

This project presents a comparative study of Machine Learning (ML) and Deep Learning (DL) models for predicting banking stock prices in Bangladesh. The study evaluates model consistency under a unified feature-engineered pipeline using multiple banking datasets.

The project focuses on:

* Banking stock price forecasting
* Feature engineering for financial time-series data
* Comparative evaluation of ML and DL models
* Consistency analysis across multiple banking datasets

---

# 🏦 Banking Datasets Used

The following banking stocks from Bangladesh were analyzed:

* BRAC Bank
* City Bank
* Eastern Bank

---

# 🤖 Models Implemented

## 🔹 Machine Learning Models

* Linear Regression
* Ridge Regression
* Support Vector Regression (SVR)
* K-Nearest Neighbors (KNN)

## 🔹 Deep Learning Models

* LSTM
* GRU
* Transformer with Time2Vec Encoding

---

# ⚙️ End-to-End Project Pipeline

```text
Raw Stock Data
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Train / Validation / Test Split
        ↓
StandardScaler
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Future Forecasting
```

---

# 🛠️ Feature Engineering

The following engineered features were generated:

* Simple Moving Average (SMA)
* Exponential Moving Average (EMA)
* Bollinger Bands
* Typical Price

These engineered features help capture:

* Trend behavior
* Volatility
* Price movement patterns

---

# 📊 Performance Evaluation Metrics

The models were evaluated using:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score

---

# 🔬 Key Research Findings

* Ridge Regression achieved the best overall performance.
* Feature engineering significantly improved prediction quality.
* Simpler ML models outperformed DL models under engineered feature conditions.
* Deep Learning models required larger datasets for stronger generalization.

---

# 🥇 Best Performing Model

## ✅ Ridge Regression

### Why Ridge Performed Best:

* Handles correlated financial features effectively
* Uses L2 Regularization to reduce overfitting
* Works efficiently with engineered features
* Provides stable performance across multiple datasets

---

---

# 🔄 Step-by-Step Workflow

## 1️⃣ Data Collection

Historical banking stock data were collected from publicly available financial sources.

---

## 2️⃣ Data Preprocessing

The preprocessing stage included:

* Handling missing values
* Sorting time-series data
* Scaling using StandardScaler
* Train-test splitting

---

## 3️⃣ Feature Engineering

Technical indicators were generated to improve learning capability.

Examples:

* SMA_10
* EMA_20
* Bollinger Bands
* Typical Price

---

## 4️⃣ Model Training

Both ML and DL models were trained using the same feature-engineered pipeline.

---

## 5️⃣ Model Evaluation

All models were evaluated fairly using the same datasets and evaluation metrics.

---

## 6️⃣ Future Forecasting

Recursive forecasting techniques were applied for future stock price prediction.

---

# 🧰 Technologies & Tools Used

## Programming Language

* Python

## Libraries

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras

## Development Environment

* Google Colab

---

# 💡 Research Insight

This study demonstrates that:

> Effective feature engineering can reduce the dependency on highly complex deep learning models for financial time-series forecasting.

---

# ⚠️ Study Limitations

* Limited dataset size
* Banking sector only
* Recursive forecasting error accumulation
* No real-time deployment

---

# 🔮 Future Research Directions

Possible future improvements:

* Real-time stock prediction
* Hybrid ML-DL architectures
* Web-based deployment
* Larger multi-sector datasets

---

# 📚 Keywords

* Banking Stock Price Prediction
* Time Series Forecasting
* Feature Engineering
* Ridge Regression
* LSTM
* Transformer
* Model Comparison

---

# 👨‍💻 Researcher

Arifur Rahman
B.Sc. in Computer Science and Engineering

---

# ⭐ Final Note

<div align="center">

### 📈 "Feature Engineering Can Sometimes Outperform Complexity"

</div>

This project focuses on comparative analysis, consistency evaluation, and feature-engineered forecasting rather than proposing a new prediction algorithm.
