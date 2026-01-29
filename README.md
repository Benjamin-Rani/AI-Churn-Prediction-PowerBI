
# Telco Customer Churn (IBM / Kaggle)/ AI Churn Prediction Project

## Overview
This project predicts customer churn using a Random Forest AI model and visualizes the results in a Power BI dashboard.

## Files
- python_3.ipynb → Python notebook with AI model, data cleaning, and feature importance  
- final_churn_predictions.csv → Predicted churn probabilities for Power BI
- Customer_Churn_Analysis.pbix → Power BI dashboard  
- README.md → Project documentation

## Key Features
- AI-driven churn prediction
- Explainable features (feature importance)
- Risk segmentation: High, Medium, Low Risk
- Interactive Power BI dashboard with KPIs, slicers, and charts

## Tools
- Python (Pandas, Scikit-Learn, Matplotlib, Seaborn)  
- Google Colab  
- Power BI
  
## What is this dataset?
- The Telco Customer Churn dataset contains information about telecom customers, such as:
- How long they’ve been customers (tenure)
- Monthly charges
- Contract type (month-to-month, one year, two year)
- Payment method
- Services they use
- Whether they left the company (churned) or not
👉 Each row = one customer

## What Was the Business Problem?
- Telecom companies lose money when customers leave.
- Business question:
- “Which customers are likely to churn, and why?”

## What I did:
1. **Cleaned and Prepared the Data**
- Removed errors and missing values
- Converted text data into usable numeric format
- Ensured each row represented one customer
📌 Why?
Clean data is required before any analysis or AI modeling.
2. **Analyzed Customer Behavior**
- I explored:
- How contract type affects churn
- Whether high monthly charges increase churn
- How long-term customers behave compared to new customers
📌 Why?
This helps understand patterns behind customer churn
3. **Built an AI Churn Prediction Model**
- Used a machine learning model to predict:
- Whether a customer will churn (Yes/No)
- The probability of churn
📌 Output:
- Churn_Pred → 0 or 1 (Will churn or not)
- Churn_Prob → % chance of churn
4. **Converted AI Results into Business Insights**
- I translated technical predictions into easy categories:
. High Risk → Very likely to churn
. Medium Risk
. Low Risk
📌 This makes AI results easy to understand and use for business decision-making.
5. **Built a Power BI Dashboard**
- I created an executive dashboard showing:
. Total customers
. Overall churn rate
. Number of high-risk customers
. Churn rate by contract type
. Interactive filters (gender, contract, payment method)
📌 Why?
So decision-makers can see and act on the insights.
