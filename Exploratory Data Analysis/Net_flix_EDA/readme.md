# 🔍 Netflix Content EDA

## 📌 Problem Statement
Performed end-to-end exploratory analysis on 8,807 Netflix
titles to uncover content trends, genre dominance, and
platform growth patterns across countries and years.

## 🛠️ Tools & Technologies
- Python, Pandas, Matplotlib, Seaborn, WordCloud
- Jupyter Notebook

## 📊 Key Questions Answered
1. What is the Movie vs TV Show split on Netflix?
2. Which genres dominate the platform?
3. How has content addition grown year-over-year?
4. Which countries produce the most Netflix content?

## 🔍 Process
1. Data Cleaning → parse dates, split multi-value columns
2. Univariate Analysis → distributions per column
3. Bivariate Analysis → genre vs rating, year vs type
4. Visualization → 8 charts telling a data story
5. Insight Summary → documented findings

## 📈 Key Findings

| # | Finding                      |  Value |
|---|---------                     |------------|
| 1 | Movies vs TV Shows split     | 69.6 % is Movies,30.4 % is TV Shows |
| 2 | Number 1 genre               | International Movies : 2752 titles |
| 3 | Content growth 2015 to 2019  | 2359.0 % |
| 4 | Top producing country        | United States ( 3689 titles) |
| 5 | Most common rating           | TV-MA ( 3211 titles) |

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/netflix_eda.ipynb
```
