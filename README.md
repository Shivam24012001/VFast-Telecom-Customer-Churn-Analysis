# VFast Telecom Customer Churn Analysis

## Overview

VFast Telecom, a leading telecom service provider in Kanpur, has observed an increase in customer churn for its broadband service. To understand the drivers of this churn and identify at-risk customer segments, a detailed analysis of customer data from the previous month has been conducted. This analysis aims to provide actionable insights to help VFast Telecom reduce churn and improve customer retention.

## Data

The analysis is based on the `Data_CustomerChurn` dataset, which includes the following information for each customer:

* **CustomerID:** Unique identifier for each customer.
* **Gender:** Customer's gender (Male or Female).
* **SeniorCitizen:** Indicates if the customer is a senior citizen (1) or not (0).
* **Tenure:** Number of months the customer has been with the company.
* **Contract:** The contract term of the customer (Month-to-month, One year, Two year).
* **PaymentMethod:** The customer’s payment method (UPI, Debit Card, Credit card (automatic)).
* **Churn:** Indicates if the customer has churned ("Yes") or not ("No").
* **MonthlyCharges:** Last month's charges paid by the customer.
* **TotalCharges:** Total charges collected from the customer over their tenure.

## Descriptive Analysis Summary

### Tenure Summary

| Particulars       | Months |
| :---------------- | :----- |
| Maximum Tenure    | 72     |
| Minimum Tenure    | 1      |
| Average Tenure    | 32     |

### Contract Summary

| Contract Type    | Number of Customers |
| :--------------- | :------------------ |
| Month-to-month   | 3875                |
| One year         | 1473                |
| Two year         | 1695                |

### Payment Method Summary

| Contract Type          | Number of Customers |
| :--------------------- | :------------------ |
| UPI                    | 3909                |
| Debit Card             | 1612                |
| Credit card (automatic) | 1522                |

### Customer Churn Summary

| Particulars             | Value   |
| :---------------------- | :------ |
| Total Customers         | 7043    |
| Number of Churned Customers | 1869    |
| Churn Rate              | 26.54%  |

## Key Areas of Analysis

The analysis focused on understanding churn patterns across the following customer segments:

* **Gender:** Investigating if there is a significant difference in churn rates between male and female customers.
* **Senior Citizens:** Comparing the churn rate of senior citizens to that of non-senior citizens.
* **Tenure:** Examining the relationship between the duration a customer has been with VFast and their likelihood of churning.
* **Contract Type:** Determining which contract types (Month-to-month, One year, Two years) have the highest and lowest churn rates.

## Key Findings

The analysis revealed the following significant insights:

### Churn Rate by Senior Citizen Status

| Senior Citizen | Total Customer | Churn Customer | Churn Rate |
| :------------- | :------------- | :------------- | :--------- |
| 0              | 5901           | 1393           | 23.61%     |
| 1              | 1142           | 476            | 41.68%     |

**Insight:** Senior citizens exhibit a significantly higher churn rate (41.68%) compared to non-senior citizens (23.61%).

### Churn Rate by Contract Type

| Contract Type    | Total Customer | Churn Customer | Churn Rate |
| :--------------- | :------------- | :------------- | :--------- |
| Month-to-month   | 3875           | 1655           | 42.71%     |
| One year         | 1473           | 166            | 11.27%     |
| Two year         | 1695           | 48             | 2.83%      |

**Insight:** The churn rate is highest for month-to-month contracts (42.71%) and decreases significantly for longer-term contracts (One year: 11.27%, Two year: 2.83%).

### Churn Rate by Gender

| Gender | Total Customer | Churn Customer | Churn Rate |
| :----- | :------------- | :------------- | :--------- |
| Female | 3488           | 939            | 26.92%     |
| Male   | 3555           | 930            | 26.16%     |

**Insight:** There is no significant difference in churn rates between male (26.16%) and female (26.92%) customers.

### Churn Rate and Tenure

**Insight:** The churn rate is inversely proportional to the tenure. Customers who have been with VFast for a longer duration are less likely to churn.

## Report For Management

1.  **Tenure and Churn:** The churn rate decreases as customer tenure increases, indicating that customers who stay with VFast longer are more likely to remain loyal.
2.  **Gender and Churn:** There is no significant difference in churn rates between male and female customers. Gender does not appear to be a primary driver of churn.
3.  **Contract Type and Churn:** Customers on month-to-month contracts have the highest churn rate, followed by one-year contracts, with two-year contracts exhibiting the lowest churn rate. This suggests that longer-term contracts foster greater customer retention.
4.  **Senior Citizens and Churn:** Senior citizens show a considerably higher churn rate compared to other customer segments. This demographic requires focused attention and potentially tailored retention strategies.

## Recommendations

Based on these findings, VFast Telecom should consider the following strategies to reduce churn and improve customer retention:

* **Incentivize Longer-Term Contracts:** Offer attractive discounts or benefits for customers willing to commit to one-year or two-year contracts.
* **Targeted Retention for Senior Citizens:** Develop specific programs and offers tailored to the needs and preferences of senior citizen customers to improve their satisfaction and reduce churn. This could include simplified billing, dedicated support channels, or relevant service bundles.
* **Focus on Early Customer Engagement:** Implement strategies to improve the experience of new customers and encourage longer tenures from the outset. This could involve proactive onboarding, excellent customer support, and demonstrating the value of VFast's services early on.
* **Further Investigation:** Conduct deeper analysis to understand the underlying reasons for the higher churn rate among senior citizens and month-to-month contract holders. This could involve surveys or qualitative research.

By implementing these recommendations, VFast Telecom can proactively address customer churn, strengthen customer loyalty, and improve overall business performance.
