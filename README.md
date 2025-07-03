## InboxShield ML: Email Spam Classifier

A machine learning-based binary classifier that detects spam emails using text preprocessing and statistical features. Built using Scikit-learn, this model analyzes email contents and filters spam using classical NLP + ML techniques.

![2022_01_Spam-Filtering-using-Bag-of-Words-1](https://github.com/user-attachments/assets/092fd9bd-7625-4763-8066-ebaa1f2f8d9c)

> 🎯 A foundational classification project demonstrating end-to-end spam detection using TF-IDF, logistic regression, and model evaluation on real-world datasets.

---

## 🧠 Problem Statement

Email spam remains one of the most prevalent digital nuisances. This project trains a supervised learning model to classify whether an email is **spam or not** based on its textual content. The pipeline includes preprocessing, vectorization, training, and performance evaluation.

---

## 🚀 Workflow

1. **Data Preprocessing**  
   - Lowercasing, punctuation removal, stopword filtering  
   - Lemmatization using `nltk`  

2. **Vectorization**  
   - TF-IDF applied on cleaned email text

3. **Modeling**  
   - Logistic Regression (primary classifier)  
   - Baseline: Naive Bayes  
   - Evaluation: Accuracy, confusion matrix, ROC AUC

4. **Result**  
   - Achieved **97.9%+ accuracy** and robust spam detection performance.

---

## 📊 Model Evaluation

| Metric       | Value        |
|--------------|--------------|
| Accuracy     | 97.98%       |
| Precision    | 98.43%       |
| Recall       | 97.65%       |
| AUC Score    | 0.991        |
