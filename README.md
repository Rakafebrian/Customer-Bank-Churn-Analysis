# Customer-Bank-Churn-Analysis
## Overview Project
This project focuses on analyzing and mitigating customer churn in the banking industry. Using Power BI, this project aims to identify churn patterns and help banks develop effective retention strategies.

**Main Objective**: Understand customer churn patterns based on demographic and financial metrics to improve retention.

**Problem**: Customer churn is a major challenge that causes revenue loss and a reduction in the customer base.

**Analysis Focus**:
1. **Identify Churn Patterns**: Determine the customer segments most at risk for churn.
2. **Demographic Analysis**: Understand customer characteristics (age, gender, credit score, balance) and group high-risk customers.
3. **KPI Development**: Create Key Performance Indicators (KPIs) to measure customer retention and loss rates.
4. **Insight Delivery**: Providing actionable insights through interactive visualizations in Power BI to support better decision-making.


## Dataset
Link : https://mavenanalytics.io/data-playground/bank-customer-churn

## Data Dictionary
## Dataset Dictionary

| Column Name      | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| CustomerId       | A unique identifier for each customer                                       |
| Surname          | The customer's last name                                                    |
| CreditScore      | A numerical value representing the customer's credit score                  |
| Geography        | The country where the customer resides (France, Spain, or Germany)          |
| Gender           | The customer's gender (Male or Female)                                      |
| Age              | The customer's age                                                          |
| Tenure           | The number of years the customer has been with the bank                     |
| Balance          | The customer's account balance                                              |
| NumOfProducts    | The number of bank products the customer uses (e.g., savings, credit card)  |
| HasCrCard        | Whether the customer has a credit card (1 = Yes, 0 = No)                    |
| IsActiveMember   | Whether the customer is an active member (1 = Yes, 0 = No)                  |
| EstimatedSalary  | The estimated salary of the customer                                        |
| Exited           | Whether the customer has churned (1 = Yes, 0 = No)                          |




## Tools
- Power BI

## Power BI Dashboard
The Dashboard Shows : 
- Key performance indicators: total customers, retained, churned, churn rate.
- Customer distribution based on: credit card ownership, membership status, gender, geographic location, tenure.
- Churn rate based on: number of products, balance, age, geographic location, membership status, credit score, tenure.

## Insight and Key Findings
Insight Based on : 
**Age**
1. High churn rate among young customers (20–30) → requires a specific retention strategy.
2. Lower churn rate among middle-aged customers (40–60) → tend to be more loyal and use a variety of products.
3. Churn rate rises again among customers over 60 → related to changes in financial priorities (retirement).

**Credit Score**
1. Low score → high churn risk (financial instability).
2. High score → low churn, more loyal, tends to use premium products.

**Account Balance**
1. Low balance → higher churn.
2. High balance → more stable & loyal.

**Tenure**
1. New customers (<3 years) → higher churn risk, need better onboarding/engagement.
2. Long tenure → better retention.

**Gender**
1. Churn rates are relatively the same between men and women, with minor differences that can be attributed to specific product preferences.

**Geography**
1. Germany has the highest churn rate (32%).
2. France and Spain are much lower (16–17%), indicating that German customers are at higher risk of churn.

**Membership Status**
1. Inactive members → high churn rate (27%).
2. Active members → low churn rate (14%).

**Products Owned**
1. Customers with 1 product → high churn (28%).
2. Customers with 2 products → low churn (8%).
3. Customers with 3 products → very high churn (83%).

**Account Balance**
1. Balance of 100K–200K → higher churn (25%).
2. Low balance (<10K) & high balance (>200K) → lower churn.

**Credit Card Ownership**
1. No significant difference → without a credit card (21%) is slightly higher than with a credit card (20%).

## Conclusion
Analysis of bank customer churn shows that churn rates are influenced by various demographic and financial factors. Customers most at risk of churn are those from Germany, aged 41–60, inactive, with only one product, a medium balance (100K–200K), and relatively new membership (<3 years). Conversely, customers with high credit scores, large balances, long membership periods, and diverse product ownership tend to be more loyal. Gender and credit card ownership do not have a significant effect on churn. These findings emphasize the importance of more targeted retention strategies, particularly for new, inactive, and German customers, as well as the need for engagement programs that can increase loyalty through product diversification and service adjustments tailored to age-specific needs. By leveraging these insights, banks can reduce churn, improve retention, and maintain long-term revenue stability.

