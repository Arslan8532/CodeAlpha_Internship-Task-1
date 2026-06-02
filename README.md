# 🏦 Credit Scoring Model - Loan Default Prediction

## 📌 Project Overview

This project predicts whether a person is **creditworthy** or not based on their financial history. It helps financial institutions decide whether to **approve or reject a loan application**.

The model uses various **classification algorithms** including Logistic Regression, Decision Tree, and Random Forest to classify customers into:
- **Low Risk (Safe)** - Loan can be given ✅
- **High Risk (Risky)** - Loan should not be given ❌

---

## 🎯 Objective

Build a machine learning model that:
- Analyzes customer financial data
- Predicts credit risk/loan default probability
- Helps banks make informed lending decisions

---

## 📊 Dataset Features

| Column Name | Description |
|-------------|-------------|
| `customer_id` | Unique customer identifier |
| `age` | Customer's age |
| `gender` | Gender (0/1 after encoding) |
| `employment_status` | Employment type (Unemployed/Part-time/Full-time) |
| `annual_income` | Yearly income in dollars |
| `account_age_months` | How long customer has had bank account |
| `avg_monthly_balance` | Average balance maintained per month |
| `num_deposits_per_month` | Number of deposits made monthly |
| `avg_deposit_amount` | Average amount per deposit |
| `debit_card_usage_frequency` | How often debit card is used |
| `debit_card_spending` | Monthly spending via debit card |
| `mobile_banking_logins` | Number of mobile banking logins |
| `online_transfer_frequency` | Frequency of online transfers |
| `atm_withdrawal_frequency` | ATM withdrawal frequency |
| `credit_score` | Credit score (300-850) |
| `num_open_loans` | Number of currently open loans |
| `total_outstanding_debt` | Total debt yet to be paid |
| `late_payment_count` | Number of late payments made |
| `loan_default_history` | Past loan default record (0/1) |
| `fraud_flag` | Any suspicious activity (0/1) |
| `loan_application_amount` | Amount requested for loan |
| `credit_risk` | **Target Variable** (1 = Risky/Default, 0 = Safe) |

---

## 🧠 Algorithms Used

| Algorithm | Type | Use Case |
|-----------|------|----------|
| **Logistic Regression** | Classification | Baseline model |
| **Decision Tree** | Classification | Interpretable rules |
| **Random Forest** | Ensemble Learning | Best performance (final model) |

---

## 📈 Evaluation Metrics

- **Accuracy** - Overall correct predictions
- **Precision** - How many predicted defaults were actual defaults
- **Recall** - How many actual defaults were captured
- **F1-Score** - Harmonic mean of precision and recall
- **ROC-AUC Score** - Model's ability to distinguish classes
- **Confusion Matrix** - Visual representation of predictions

---

## 🛠️ Tech Stack

| Tool/Library | Purpose |
|--------------|---------|
| Python 3.x | Programming language |
| Pandas, NumPy | Data manipulation |
| Scikit-learn | Machine learning models |
| Matplotlib, Seaborn | Visualization |
| Joblib | Model saving/loading |
| Google Colab | Development environment |

---




