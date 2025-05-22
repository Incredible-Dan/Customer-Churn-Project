# Customer Churn Prediction Project 🧠📉

This project predicts whether a customer will churn (stop using a service) based on their historical data. It’s a classic **binary classification problem** solved using **Random Forest** and **XGBoost** models.

---

## 🔍 Problem Statement

Telecommunication companies suffer significant revenue loss due to customer churn. This project builds a machine learning model to identify customers at risk of churning, enabling businesses to take proactive measures to retain them.

---

## 📌 Project Objectives

- Predict if a customer will churn based on behavior and service usage patterns.
- Build a user-friendly web interface using **Streamlit** for live predictions.
- Provide business insights using explainable AI techniques.

---

## 📁 Dataset

- **Source**: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records**: 7,043 customers
- **Features**: Demographics, service plans, contract types, payment methods, and more
- **Target**: `Churn` (Yes/No)

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- SHAP (Model Explainability)
- Streamlit (Deployment)

---

## 🔧 Project Workflow

1. **Data Preparation**
   - Handled missing and inconsistent values
   - Encoded categorical variables
   - Scaled numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution
   - Identified correlations between features

3. **Model Training**
   - Trained using Random Forest and XGBoost
   - Evaluated via confusion matrix, precision, recall, F1-score, and ROC-AUC

4. **Explainability**
   - Used SHAP to interpret feature contributions to predictions

5. **Deployment**
   - Saved model using `joblib`
   - Built a Streamlit app for real-time churn prediction

---

## 📊 Model Performance

- **Best Model**: XGBoost
- **Accuracy**: ~85%
- **ROC AUC**: ~0.89
- **Top Features**: Contract type, tenure, monthly charges, payment method

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/your-username/customer-churn-prediction.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the Streamlit app
streamlit run app.py
```

## 🧑‍💻 Author

**Daniel Idoko Chinweokwu**  
[LinkedIn](https://www.linkedin.com/in/daniel-idoko-chinweokwu/) • [Portfolio](https://sites.google.com/view/dananalytics/portfolio)

---

## 🌟 Feedback

If you like this project, please ⭐ the repo.  
Have suggestions or questions? Open an issue or contact me on LinkedIn!




