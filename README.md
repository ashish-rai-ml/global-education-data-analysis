# Global Education Dropout Risk Analysis

## 📌 Overview

This repository contains an exploratory data analysis and machine learning
classification approach to identifying education systems at risk of high
dropout levels, using curated global education indicators.

The analysis is based on a cleaned version of World Bank–inspired data
containing key education metrics for many countries over time.

---

## 📊 Dataset

The dataset includes the following indicators by country and year:

- Primary completion rate (%)
- Lower secondary completion rate (%)
- Out-of-school children (%)
- Pupil–teacher ratio
- Education expenditure (% of GDP)

The target variable *Dropout_Risk* was derived from the percentage of
out-of-school children using a policy-informed threshold.

---

## 🧠 Methodology

1. **Problem Definition**  
   Dropout risk is identified using the percentage of out-of-school children.

2. **Data Preparation**  
   Selected relevant features and created binary risk labels.

3. **Exploratory Data Analysis**  
   Evaluated trends and distributions to understand underlying patterns.

4. **Modeling**  
   - Logistic Regression (baseline)
   - Random Forest Classifier (final model)

5. **Evaluation & Interpretation**  
   Examined classification metrics and feature importance to derive
   actionable insights.

---

## 📈 Key Insights

- Completion rates and pupil–teacher ratios are strongly linked with dropout risk.
- Higher out-of-school percentages identify vulnerable education systems.
- Model interpretation supports targeted policy recommendations.

---

## 🛠 Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

---

## 📁 Repository Contents

- `Global_Education_Dropout_Risk_Analysis.ipynb`: Main analysis notebook  
- `worldbank_education_clean.csv`: Cleaned dataset file  
- `README.md`: Project overview

---

## 📌 License

This repository is provided for educational purposes.
