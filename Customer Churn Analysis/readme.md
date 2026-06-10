# 📉 Customer Churn Analysis

## 📌 Problem Statement
Analyzed 7,043 telecom customer records to identify the key
drivers of churn and build a predictive model to flag
at-risk customers, enabling proactive retention strategies.

## 🛠️ Tools & Technologies
- Python, Pandas, Seaborn, Scikit-learn
- Jupyter Notebook

## 📊 Key Questions Answered
1. What is the overall churn rate?
2. Which contract type has the highest churn?
3. Does tenure affect churn probability?
4. Can we predict churn with >80% accuracy?

## 🔍 Process
1. Data Cleaning → encode categories, handle nulls
2. EDA → churn rate by segment, correlation heatmap
3. Feature Engineering → tenure buckets, binary encoding
4. Modeling → Logistic Regression + Random Forest
5. Evaluation → Accuracy, Precision, Recall, F1

## 📈 Key Findings
 
## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis.ipynb
```
