# Customer Churn Prediction

## Project Overview
This project predicts which telecom customers are likely
to cancel their service using Machine Learning.
Built as part of my Data Science portfolio.

## Problem Statement
Customer churn costs companies millions every year.
This model helps identify at-risk customers BEFORE
they leave so the company can take action early.

## Dataset
- Source: Telco Customer Churn (Kaggle)
- 7043 customers, 21 features
- Target variable: Churn (Yes/No)

## Tools and Technologies
- Python 3
- Pandas, NumPy — data manipulation
- Matplotlib, Seaborn — data visualization
- Scikit-learn — machine learning

## Project Structure
01_explore_data.ipynb  → Data loading and exploration
02_model.ipynb         → Data cleaning and ML model
03_storytelling.ipynb  → Business insights and charts

## Key Results
- Model Accuracy: 79.77%
- Top churn predictors: TotalCharges, tenure, MonthlyCharges
- Month-to-month customers churn 3x more than yearly customers
- New customers (0-12 months) are at highest risk

## Business Recommendations
1. Offer discounts to convert month-to-month customers
   to yearly contracts
2. Create onboarding program for new customers
   in their first 3 months
3. Monitor high monthly charge customers closely

## How to Run
1. Clone this repository
2. Install requirements: pip install -r requirements.txt
3. Open Jupyter Notebook
4. Run notebooks in order: 01 → 02 → 03

## Author
Veera Venkata Naga Surya Jaya Sai Padala
Master's in Applied Computer Science
