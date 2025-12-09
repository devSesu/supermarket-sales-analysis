# Supermarket Sales Analysis & Predictive Modeling

This project analyzes supermarket transactional data to uncover insights about customer behavior, product performance, time-based sales trends, and branch profitability.  
A simple linear regression model is also built to predict **gross income** using features such as unit price and quantity.

Project Objectives
- Analyze sales performance across branches and product lines.
- Compare revenue contribution from different customer types (Members vs Normal).
- Identify peak sales hours and busiest days of the week.
- Explore payment method preferences.
- Understand correlations between numerical features.
- Build a predictive model to estimate gross income.
- Provide actionable business insights to guide decision-making.

Dataset Description
The dataset contains **1,000 supermarket transactions** across three branches (A, B, C).  
Key fields include:

- Invoice ID, Branch, City
- Customer Type, Gender**
- Product Line**
- Unit Price, Quantity**
- Tax (5%), Total Cost, Gross Income**
- Rating
- Payment Method
- Date, Time

  Additional engineered features in this notebook:
- Day, Month, Year
- Weekday
- Hour (derived from Time)

  Busisiness Questions Answered
1. Which branch generates the highest sales?
2. Which product lines perform best?
3. Do Members or Normal customers bring more revenue?
4. Which payment methods are most used?
5. What are the hourly and daily sales patterns?
6. What features correlate most strongly with income?
7. Can we accurately predict gross income using unit price and quantity?
8. Are there anomalies or patterns in residuals?

             Modeling
A Linear Regression model was built using:

- Features: Unit Price, Quantity  
- Target: Gross Income  

Model performance:
- MAE: ~0.68  
- R² Score: ~0.99  
- Residuals: Distributed around zero, indicating a healthy model.


Analysis Techniques Used
- Exploratory Data Analysis (EDA)
- Time-series feature engineering
- Correlation heatmap
- Grouped bar charts and distribution plots
- Regression modeling
- Residual diagnostics

Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  
```bash
pip install -r requirements.txt
