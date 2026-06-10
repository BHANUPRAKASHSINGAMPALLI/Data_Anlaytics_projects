# 🏠 House Price Prediction

## 📌 Problem Statement
Built a regression model on 1,460 housing records to predict
sale prices based on 79 features including location, size,
and quality — achieving an R² score above 0.85.

## 🛠️ Tools & Technologies
- Python, Pandas, Scikit-learn, XGBoost, Matplotlib
- Jupyter Notebook

## 📊 Key Questions Answered
1. Which features most influence house price?
2. How accurately can we predict sale price?
3. What's the impact of location (neighborhood) on price?
4. Do renovation years affect sale value?

## 🔍 Process
1. Data Cleaning → handle 19 null columns, encode categoricals
2. EDA → price distribution, correlation heatmap
3. Feature Engineering → new features from existing columns
4. Modeling → Linear Regression → Random Forest → XGBoost
5. Evaluation → RMSE, MAE, R² Score

## 📈 Key Findings
 

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/house_price_prediction.ipynb
```
