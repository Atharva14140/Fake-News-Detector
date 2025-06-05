# Fake-News-Detector
A machine learning project to classify news as REAL or FAKE using TF-IDF and PassiveAggressiveClassifier

---

## 📌 Overview

This project uses Natural Language Processing and a *Passive-Aggressive Classifier* to detect whether a news article is real or fake. The text data is vectorized using *TF-IDF*, and the classifier achieves over 90% accuracy on the test set. It's a concise yet practical example of ML for real-world problems.

---

## 🚀 Features

- Dataset of labeled news articles (REAL or FAKE)
- Preprocessing and TF-IDF vectorization
- Model training using PassiveAggressiveClassifier from scikit-learn
- Live demo with *Gradio UI* for real-time predictions

---

## 📁 Dataset

- *File:* news.csv  
- *Columns:* 
  - text: news content
  - label: FAKE or REAL
- Dataset source: This repo contains a csv file of fake news data used in this article. https://opendatascience.com/how-to-build-a-fake-news-classification-model/

---

## 🧪 Dependencies

Installed via pip:
