# 💳 Credit Card Fraud Detection using Machine Learning

### 🔍 Overview
This project focuses on detecting fraudulent credit card transactions using various Machine Learning algorithms.  
Due to the highly imbalanced nature of the dataset (~0.17% fraud cases), the project emphasizes **class imbalance handling**, **model comparison**, and **performance evaluation beyond accuracy**.

---

## 📂 Dataset
- Source: Kaggle – **Credit Card Fraud Detection**
- Total Records: **284,807**
- Fraudulent Transactions: **0.17%**
- Target Column: **`Class`** (0 = Legit, 1 = Fraud)

---

## 🧠 Objectives
- Analyze anonymized credit card transaction data
- Handle data imbalance and scale features
- Train multiple ML models
- Compare model performance using key fraud-specific metrics
- Identify the most effective model for fraud prediction

---

## 🛠 Tech Stack
| Category | Tools |
|---------|-------|
| Language | Python |
| ML Libraries | Scikit-Learn, XGBoost |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Imbalance Handling | SMOTE (imbalanced-learn) |
| Notebook | Jupyter Notebook |

---

## 🚀 Machine Learning Models Used
| Model |
|-------|
| Logistic Regression |
| Decision Tree |
| Random Forest |
| Support Vector Machine (SVM) |
| XGBoost |

---

## 🔁 Project Workflow
1. Import dataset and perform EDA (`head()`, `info()`, `describe()`, etc.)
2. Feature scaling using **StandardScaler**
3. Train-test split (80/20)
4. Class imbalance handling using **SMOTE**
5. Train multiple ML models
6. Evaluate using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC
7. Compare results and determine best model

---

## 📊 Performance Summary
| Model | Best Metric |
|-------|-------------|
| XGBoost | ⭐ Highest ROC-AUC |
| Random Forest | Excellent overall performance |
| Logistic Regression | Good baseline |
| SVM | Average |
| Decision Tree | Moderate |

🔑 **XGBoost ranked best overall and is recommended for real-world deployment.**

---

## 📁 Project Structure
