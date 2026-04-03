# PowerCo Churn Analysis

## Overview
This project explores customer behavior, pricing structures, and churn patterns for PowerCo using exploratory data analysis (EDA). The goal is to identify key factors influencing customer churn and generate insights to support data-driven decision-making.

---

## Data Description
The analysis is based on three datasets:

- **Customer Data**: Includes consumption metrics, tenure, and forecasted usage
- **Pricing Data**: Contains variable and fixed pricing across different time periods
- **Churn Data**: Indicates whether a customer has churned or not

---

## Customer Behavior Insights

Customer consumption variables, including electricity and gas usage over the last 12 months, as well as forecasted consumption, show consistent right-skewed distributions. This indicates that most customers consume moderate amounts of energy, while a smaller group represents high-consumption users.

Churned customers consume significantly less energy compared to retained customers, using less than half the electricity and approximately one-third of the gas. Despite this, churned customers generate higher net margins on average, suggesting they are a disproportionately valuable segment.

Customer tenure is concentrated between 3 and 6 years, with a sharp decline after year 7. Churned customers tend to have shorter tenure, indicating lower engagement and weaker long-term retention.

---

## Pricing Structure Insights

Variable pricing is relatively standardized during off-peak periods, with most customers paying similar rates. However, peak and mid-peak variable prices are right-skewed, indicating that a subset of customers pays significantly higher rates, likely due to contract differences.

Fixed pricing follows a similar pattern for peak and mid-peak periods, with most customers paying moderate charges and a minority facing higher costs. Off-peak fixed pricing shows a bimodal distribution, revealing two distinct pricing tiers within the customer base, likely representing legacy and standard contracts.

---

## Churn and Pricing Relationship

Off-peak variable pricing shows no difference between churned and retained customers, indicating it does not influence churn.

Peak variable pricing is slightly higher for churned customers, and while the difference is small, it may accumulate over time due to higher usage during peak periods.

Off-peak fixed pricing shows only a marginal difference and is unlikely to drive churn independently.

Peak fixed pricing is the most significant factor, with churned customers paying approximately 33% more than retained customers. This substantial difference suggests that higher fixed charges may contribute directly to customer dissatisfaction and switching behavior.

---

## Key Insight

Churned customers represent a low-consumption but high-margin segment. Pricing disparities, particularly in peak fixed charges and tiered pricing structures, appear to play a critical role in influencing churn. Addressing these disparities through pricing optimization and targeted retention strategies may help reduce customer attrition and protect profitability.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
