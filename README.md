# Fake News Detection Using Machine Learning 📰🤖

> 🔗 **Dataset Source**: [Fake and Real News Dataset – Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

This project implements a **Fake News Detection** system using classical Machine Learning models on a labeled dataset of fake and real news articles.

## 📌 Overview

The goal is to classify news articles as **real** or **fake** based on their textual content. The dataset contains two types of news articles labeled accordingly. We used standard preprocessing techniques followed by training and evaluating multiple ML models.

## ✅ Features

- Text preprocessing with stemming and vectorization (TF-IDF)
- Models used:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Multinomial Naive Bayes (MNB)
  - Random Forest Classifier
- Performance comparison across all models
- Model serialization (exporting best-performing model)

## 📊 Accuracy Results

| Model                  | Accuracy   |
|------------------------|------------|
| Logistic Regression    | 99.05%     |
| SVM                    | 99.50%     |
| Multinomial Naive Bayes | 94.47%    |
| Random Forest          | **99.85%** ✅ |

## 🧪 How It Works

1. Load and clean the dataset
2. Apply stemming to text
3. Convert text to TF-IDF vectors
4. Split data into training and test sets
5. Train multiple classifiers
6. Evaluate and compare results
7. Export best model (Random Forest)

## 📁 Files

- `FakeNewsDetection.ipynb` – Main Jupyter Notebook
- `README.md` – Project documentation
- `requirements.txt` – Dependencies (optional)
- `model.pkl` – Trained Random Forest model (if exported)

## 🚀 Future Work

- Add a web interface using Flask or Streamlit
- Deploy as a live app
- Improve performance with ensemble methods or DL

## 📬 Contact

Feel free to connect or give feedback! This project was built with learning and research in mind.

