# 🎫 Support Ticket Classification & Prioritization System

## 📌 Overview

This project builds a machine learning–based NLP system to automatically:

- Classify support tickets into categories  
- Assign priority levels (High / Medium / Low)  
- Improve ticket routing efficiency  

This mirrors real-world customer support automation systems used in SaaS and IT platforms.

---

## ⚙️ Tech Stack

- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF
- Logistic Regression
- Seaborn & Matplotlib

---

## 🧠 Features Implemented

- Text preprocessing (lowercasing, stopword removal, punctuation cleaning)
- Custom domain-specific stopwords
- TF-IDF vectorization (unigrams & bigrams)
- Multi-class ticket classification
- Stratified train-test splitting
- Logistic Regression with class imbalance handling
- Accuracy, Precision, Recall & F1-score evaluation
- Confusion Matrix visualization
- Rule-based priority assignment system
- Operational business explanation

---

## 📊 Model Performance

- Accuracy ≈ 85%
- Strong class-wise F1-scores across 8 categories
- Balanced class-weight implementation for fairness

---

## 🚨 Priority Assignment Logic

Tickets are assigned priority based on:

- Urgency keywords
- Critical operational categories
- Business rule-based severity logic

---

## 🎯 Business Impact

This system helps support teams:

- Reduce manual ticket sorting time
- Identify urgent issues quickly
- Improve response time
- Reduce operational backlog

---

## 🚀 How to Run

```bash
pip install -r requirements.txt