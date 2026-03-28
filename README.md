# 📊 Amazon Product Review Analysis & Sentiment Prediction

## 🚀 Project Overview

This project focuses on analyzing Amazon product reviews and building a machine learning model to predict whether a review is **positive or negative** based on customer feedback.

The goal is to extract meaningful insights from review data and develop a predictive model that can assist in understanding customer sentiment.

---

## 🎯 Problem Statement

Given Amazon product reviews, predict whether a review is **positive (rating ≥ 4)** or **negative (rating < 4)** using machine learning techniques.

---

## 📂 Dataset

* Source: Kaggle (Amazon Product Reviews Dataset)
* The dataset contains product details, customer reviews, ratings, and metadata.

👉 Note: Due to large file size, dataset is not included in this repository.
You can download it from Kaggle.

---

## 🧹 Data Preprocessing

* Selected relevant features from raw dataset
* Handled missing values
* Removed duplicate records
* Simplified product categories
* Created new feature: **review_length**
* Combined review title and text for better analysis

---

## 📊 Exploratory Data Analysis (EDA)

* Analyzed distribution of product ratings
* Identified top brands based on number of reviews
* Studied distribution of review lengths
* Explored relationship between rating and review length

### 🔍 Key Insights:

* Majority of reviews are **positive (4 & 5 stars)** indicating dataset imbalance
* Mid-range ratings tend to have **longer reviews**
* Certain brands dominate the review count

---

## ⚙️ Feature Engineering

* Converted ratings into binary labels:

  * `1 → Positive`
  * `0 → Negative`
* Applied **TF-IDF Vectorization** to convert text into numerical features
* Combined text features with numerical features

---

## 🤖 Model Building

* Implemented:

  * Logistic Regression
  * Random Forest Classifier
* Used train-test split for evaluation

---

## 📈 Model Evaluation

### 🔹 Final Model: Logistic Regression

* Accuracy: **89%**

### 🔹 Classification Report:

* Balanced performance across classes
* Improved detection of negative reviews after handling imbalance

### 🔹 Confusion Matrix:

* True Positives: 176
* True Negatives: 33
* False Positives: 10
* False Negatives: 17

---

## 🧠 Key Learnings

* Real-world datasets are often **imbalanced**
* Accuracy alone is not a reliable metric
* Confusion matrix helps understand model performance deeply
* Feature engineering significantly impacts results

---

## 🔥 Conclusion

The project successfully demonstrates how machine learning can be used to analyze customer sentiment and predict review outcomes. Handling class imbalance improved model reliability, making it more practical for real-world applications.

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

## 📌 Future Improvements

* Hyperparameter tuning
* Use advanced NLP models (e.g., BERT)
* Deploy model as a web application

---

## 👤 Author

Praveena Pawar
