<p align="center">
  <img src="credit_card.png" alt="Credit Card Fraud Detection" width="700"/>
</p>

# 💳 Credit Card Fraud Detection

This project builds a machine learning model to detect fraudulent credit card transactions using the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

---

## 📊 Dataset

- 284,807 transactions
- 492 fraudulent (Class 1), rest are legitimate (Class 0)
- Highly imbalanced dataset

---

## 💡 Project Highlights

- Preprocessing with `StandardScaler` and SMOTE oversampling
- Models: Logistic Regression (baseline), Random Forest (best)
- Evaluation using accuracy, precision, recall, and F1-score
- Random Forest achieved:
  - Accuracy: **99.97%**
  - Precision: **89%**
  - Recall: **86%**
  - F1-Score: **88%**

---

## 🧪 How to Run

1. Upload `creditcard.csv` to Colab or Jupyter
2. Run all notebook cells
3. Final model is saved as `credit_fraud_rf_model.pkl`

---

## 🛠 Tech Stack

- Python
- Pandas, Scikit-learn
- imbalanced-learn (SMOTE)
- Seaborn, Matplotlib
- Google Colab

---

## 🚀 Future Improvements

- Try XGBoost or LightGBM for even better performance
- Deploy as a web API using Flask or Streamlit
- Add time-based feature engineering

---

## 📁 Files

- `fraud_detection.ipynb` – Main notebook
- `credit_fraud_rf_model.pkl` – Saved Random Forest model
- `README.md` – Project summary

---
