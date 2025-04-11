# 🕵️‍♂️ Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using various machine learning models. It leverages a real-world dataset with highly imbalanced classes, emphasizing precision, recall, and ROC-AUC for effective fraud identification.

## 📁 Dataset

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It includes anonymized features (V1–V28), along with `Time`, `Amount`, and a `Class` label:
- `Class = 1`: Fraud
- `Class = 0`: Legitimate

> **Note:** Due to confidentiality, the original dataset is not included. You can download it from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 📊 Features
- **Time**: Seconds elapsed between each transaction and the first transaction in the dataset.
- **V1–V28**: Principal components obtained using PCA for confidentiality.
- **Amount**: Transaction amount.
- **Class**: Label indicating fraud.

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Machine Learning Models:

  - Random Forest


## 📌 Project Highlights
- Addressed class imbalance using evaluation metrics like **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**.
- Compared multiple models to identify the best performer for fraud detection.
- Visualized confusion matrices and ROC curves for performance insight.


  ## 🎓 What I Learned

- The importance of **handling imbalanced datasets** in classification problems.
- How to **evaluate models beyond accuracy**, especially in domains where false negatives are critical.
- Implementation and comparison of several **classification algorithms**.
- How to use **standardization techniques** like `StandardScaler` to improve model performance.
- Visualizing and interpreting results using **confusion matrices** and **ROC curves**.
- The practical trade-offs between **precision and recall** when detecting rare events like fraud.



