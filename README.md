
# 📰 Fake News Detection Using Machine Learning

This project uses machine learning to identify whether a given news article is *real* or *fake*. It aims to address the growing problem of misinformation online by using a trained model on labeled datasets.

## 📁 Project Overview

This Jupyter notebook includes:

- Data cleaning and preprocessing (removing stopwords, punctuation, etc.)
- Feature extraction using *TF-IDF*
- Model training using *PassiveAggressiveClassifier*
- Evaluation using *accuracy score and confusion matrix*

## 🔍 Dataset

The dataset used contains labeled news articles (real or fake), and it is loaded directly from a CSV file. Make sure the CSV file is in your working directory or properly linked.

https://www.kaggle.com/c/fake-news/data?select=train.csv

## 🚀 How to Run

1. Clone the repo or open the notebook in Google Colab.
2. Upload your dataset (news.csv).
3. Run all cells in order.

## 📊 Results

The classifier achieves over *90% accuracy* in most runs, making it effective for binary fake news classification.

## 🛠 Libraries Used

- pandas
- sklearn
- numpy
- PassiveAggressiveClassifier
- TfidfVectorizer

## 🙌 Contributions

Developed by *Saman Tariq*  
Feel free to contribute or suggest improvements by opening a pull request.

## 📎 Link to Notebook

(https://github.com/Samanchanda/fake_news_prediction/blob/main/fake-news-detection.ipynb)

