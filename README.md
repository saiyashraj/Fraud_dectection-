# Fraud_dectection-
This a ml-model to dectect a fraud 
# 💳 Fraud Detection Web App

This is a Streamlit-based web application that predicts whether a financial transaction is potentially fraudulent. The model used is a Logistic Regression classifier trained with a full preprocessing pipeline that includes scaling and encoding.

---

## 📌 Features

- User-friendly interface built with Streamlit
- Accepts transaction inputs like type, amount, sender/receiver balances
- Uses a trained machine learning pipeline for prediction
- Displays whether the transaction is **fraudulent** or **legitimate**

---

## 🧠 Model Info

- **Algorithm**: Logistic Regression (`class_weight='balanced'`)
- **Preprocessing**: 
  - `StandardScaler` for numeric features
  - `OneHotEncoder` for categorical features (drop='first')
- **Pipeline**: Entire pipeline (preprocessor + classifier) saved as `fraud_detection.pkl`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/fraud-detection-streamlit.git
cd fraud-detection-streamlit

