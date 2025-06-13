# 💳 Credit Card Fraud Detection

This project uses machine learning to detect fraudulent credit card transactions using a real-world dataset. The goal is to identify patterns that separate legitimate transactions from fraudulent ones, despite significant class imbalance.

## 📌 Project Objectives

- Analyze and clean a credit card transaction dataset.
- Handle class imbalance using resampling techniques (e.g., SMOTE).
- Train and evaluate classification models like SVM, Random Forest, and XGBoost.
- Visualize model performance with confusion matrices, ROC-AUC curves, and precision-recall analysis.

---

## 📊 Dataset

The dataset used is from kaggle: https://www.kaggle.com/code/youssefelbadry10/credit-card-fraud-detection/input
Although this dataset closely mirrors real-world financial data in structure and complexity, it is likely synthetic or partially simulated for privacy and security reasons. This is common in fraud detection datasets due to the sensitive nature of financial and personally identifiable information (PII).

---

## 🧠 Models Used

- Support Vector Machine (SVM)
- Random Forest
- XGBoost

Techniques for handling class imbalance:
- SMOTE (Synthetic Minority Oversampling Technique)

---

## 📈 Evaluation Metrics

Because of the imbalanced dataset, accuracy isn't a reliable metric. Instead, we use:

- Precision
- Recall
- F1-score
- ROC-AUC score
- Confusion Matrix

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **XGBoost**
- **Imbalanced-learn**

---
##🔚 Conclusion
This project shows how effective preprocessing, SMOTE oversampling, and proper evaluation metrics can dramatically improve the detection of fraudulent transactions. Even simple models like Logistic Regression benefit from thoughtful handling of class imbalance.

> ✨ Note: This project is a work in progress and may receive future updates.
---
##👩🏾‍💻 Author
Divine U. Efiok
Computer Engineering + Math @ Texas A&M University
📫 Reach me on LinkedIn or GitHub to connect or collaborate!


