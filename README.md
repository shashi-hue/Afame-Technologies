# 🛡️ Credit Card Fraud Detection

**Internship Project – Afame Technologies**

---

## 📌 Objective
The goal of this project is to build a machine learning model that can detect fraudulent credit card transactions using real-world customer and transaction data.

---

## 📁 Dataset
- Simulated credit card transaction dataset (2019–2020)
- Includes data for 1000 customers across 800 merchants
- Contains legitimate and fraudulent transactions
- [Dataset Source (Google Drive)](https://drive.google.com/drive/folders/1sDzIPjCmNZ9lWaXfcAqIIx4NZchYG4OP?usp=sharing)

---

## 🔧 What I Did

- Explored the data: class imbalance, missing values, anomalies
- Performed feature engineering:
  - Extracted hour, day, weekday from transaction time
  - Calculated age from date of birth
- Preprocessed data:
  - Encoded categorical variables like gender and category
  - Scaled numeric features
- Trained and evaluated 5 models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Linear SVC

---

## 📊 Evaluation Metrics

Because the dataset is imbalanced (very few fraud cases), I used:

- **Precision**
- **Recall**
- **F1-score**
- **ROC-AUC** (Area Under the Curve)

---

## 🏆 Results

| Model               | AUC Score |
|---------------------|-----------|
| Random Forest       | **0.97**  ✅ Best
| Decision Tree       | 0.89      |
| Logistic Regression | 0.83      |
| Linear SVC          | 0.83      |

🟢 **Random Forest** clearly performed the best, capturing fraud patterns effectively while avoiding overfitting.

---

