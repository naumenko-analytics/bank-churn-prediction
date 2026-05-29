# Bank Customer Churn Prediction
### Naumenko Analytics LLC

## Overview
Machine learning project to predict bank customer churn using 
10,000 customer records. Identifies customers likely to leave 
the bank, enabling targeted retention strategies.

## Key Findings
- **Random Forest** outperforms Logistic Regression significantly
- **85.7% accuracy** with Random Forest vs 80.5% Logistic Regression
- **Age** is the strongest predictor of churn (25.49% importance)
- German customers churn at 2x the rate of French/Spanish customers
- Customers aged 40-50 with high balances are highest risk

## Business Recommendation
Target retention efforts on customers aged 40-50 with high 
account balances, particularly in Germany. Offering additional 
products to single-product customers would likely reduce churn.

## Model Performance

| Metric | Logistic Regression | Random Forest |
|---|---|---|
| Accuracy | 80.50% | 85.70% |
| Churn Precision | 59% | 76% |
| Churn Recall | 14% | 43% |
| Churn F1-Score | 0.23 | 0.55 |
| Churners Caught | 58 / 407 | 175 / 407 |

## Technologies Used
- Python 3.14
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Dataset
Bank Customer Churn Prediction dataset - 10,000 customers, 
12 features including credit score, age, balance, tenure, 
country, gender, and products.

## Author
Maksym Naumenko
Quantitative Analyst
Naumenko Analytics LLC
www.naumenkoanalytics.com
