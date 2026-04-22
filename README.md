# Sentiment Analysis of Cryptocurrency market using machine learning

This project analyzes the relationship between public sentiment and cryptocurrency price movements using real-world data.

## 📌 Overview

We collected and combined cryptocurrency-related data from multiple sources, including news headlines, social media (tweets), and Bitcoin price data (2018–2023). The dataset consists of over 240,000 records.

## 🎯 Objective

To understand how market sentiment impacts cryptocurrency price trends and to build models that can predict price movement based on sentiment.

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* Matplotlib / Seaborn

## ⚙️ Features

* Data preprocessing and cleaning
* Sentiment analysis on text data
* Feature engineering combining sentiment + price data
* Machine learning models for prediction
* Visualization of trends and insights

## 📊 Results

The project demonstrates a correlation between sentiment polarity and market movements, showing how social and news sentiment can influence crypto prices.

## 📈 Model Performance
-SVM — LinearSVC         Acc: 78.0%  F1: 78.1% ← BEST
-Logistic Regression     Acc: 76.7%  F1: 76.8%
-KNN (k=5)               Acc: 51.3%  F1: 51.4%
-Decision Tree           Acc: 46.7%  F1: 40.5%

## 🚀 Future Work

* Use deep learning (LSTM, BERT)
* Real-time sentiment tracking
* Deployment as a web dashboard

## 📁 Dataset

Data sourced from Kaggle (2018–2023 crypto data)

## 👨‍💻 Author

Yuvraj, Anshil, Depanshu
