# 💳 Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. Due to the **extreme class imbalance** in the dataset, special techniques like **undersampling** and **SMOTE (Synthetic Minority Over-sampling Technique)** were applied to improve model performance.

---

## 📊 Dataset

- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Features: 28 anonymized variables (V1 to V28), along with `Amount`, `Time`, and `Class` (0 = non-fraud, 1 = fraud)
- Transactions: 284,807 total rows  
- Fraudulent cases: 492 (~0.17%)

> ⚠️ **Note**: The dataset is not included due to size constraints.  
Please download `creditcard.csv.zip` from Kaggle and place it in the `/data` folder.

---

## ⚙️ Project Structure

credit-card-fraud-detection/
├── data/ # Raw dataset (creditcard.csv.zip)
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_model_undersampling.ipynb
│ └── 03_model_SMOTE.ipynb
├── models/ # (Optional) Trained models, if saved
├── app.py # (Optional) Streamlit app (experimental)
├── reports/ # Visualizations and evaluation results
└── README.md # You're here



