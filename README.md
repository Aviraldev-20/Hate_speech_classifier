# Hate_speech_classifier
Here’s a **README.md** draft for your Hate Speech Classifier repository:

---

# 🛡️ Hate Speech Detection Classifier

## 📌 Overview

This project implements a **machine learning-based text classification model** to detect **Hate Speech**, **Offensive Language**, and **Neutral Speech** in tweets. It includes **data preprocessing**, **exploratory data analysis (EDA)**, **text cleaning**, and **model training**, aiming to improve content moderation and promote safe online communication.

## 📂 Dataset

* **Source:** Twitter Dataset (CSV format)
* **Classes:**

  * `Hate Speech`
  * `Offensive Language`
  * `No Hate or Offensive Language`

## 🔍 Project Workflow

1. **Data Loading & Preparation**

   * Load CSV dataset.
   * Map numeric classes to descriptive labels.
   * Balance dataset through oversampling.

2. **Exploratory Data Analysis (EDA)**

   * Class distribution visualization using **Seaborn**.
   * Insights into imbalance before oversampling.

3. **Text Preprocessing**

   * Lowercasing and punctuation removal.
   * Stopword removal using **NLTK**.
   * Stemming with **Snowball Stemmer**.
   * Removal of URLs, numbers, and special characters.

4. **Feature Extraction & Model Building**

   * **CountVectorizer** for text vectorization.
   * **Decision Tree Classifier** for classification.
   * Evaluation using **confusion matrix** and **accuracy score**.

## 🛠️ Technologies Used

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **NLTK** (stopword removal, stemming)
* **Scikit-learn** (CountVectorizer, DecisionTreeClassifier, model evaluation)


## 🚀 Future Improvements

* Experiment with advanced models like **Random Forest**, **XGBoost**, or **BERT** for better accuracy.
* Apply lemmatization instead of stemming.
* Integrate with a web-based interface using **Flask** or **FastAPI** for real-time predictions.

---
