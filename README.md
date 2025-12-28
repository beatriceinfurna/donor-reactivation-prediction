# Predicting Donor Reactivation for a Non-Profit Campaign

## Project Overview
Non-profit organizations often rely on reactivation campaigns to re-engage inactive donors. 
However, contacting all past donors is costly and inefficient.

The objective of this project is to predict which inactive donors are most likely to donate again, 
allowing the organization to optimize campaign targeting and maximize return on investment.

---

## Business Objective
- Identify inactive donors with a high probability of donating again
- Improve campaign efficiency compared to random donor selection
- Support marketing decisions using data-driven insights

---

## Data Description
The project is based on multiple datasets provided by a non-profit organization, including:
- Donor demographic information
- Historical donation records
- Previous reactivation campaign selections
- Campaign cost information

To ensure a realistic modeling approach, only information available before each campaign was used, 
preventing data leakage.

---

## Methodology
1. Data cleaning and exploratory analysis  
2. Target variable construction (donation amount ≥ €30)  
3. Feature engineering using historical donation behavior  
4. Model training and comparison  
5. Model evaluation using:
   - AUC
   - Lift curve
   - Cumulative gains  
6. Business impact analysis based on campaign costs

---

## Results
- The predictive model outperformed random targeting strategies
- High-potential donors could be identified within a limited subset of the population
- The approach demonstrated clear potential to increase campaign profitability

---

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Data visualization libraries
- Powerpoint for case presentation

---

## Team & Contribution
This project was developed as part of a group assignment.

My personal contribution included:
- Feature engineering
- Model training and evaluation
- Interpretation of model performance and business impact
- Presentation slides regarding the business case
