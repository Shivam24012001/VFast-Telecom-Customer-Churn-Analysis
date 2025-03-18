# VFast Telecom Customer Churn Analysis 📊

## Overview 🚀

VFast Telecom, a leading telecom service provider in Kanpur 🇮🇳, has noticed an increase in customer churn for its broadband service. To understand why customers are leaving and identify those most likely to churn, we've dug into the data from last month. Our goal? To give VFast Telecom the insights they need to keep their customers happy and reduce churn! 🤝

## Data 💾

We looked at the `Data_CustomerChurn` dataset, which tells us a lot about each customer:

* **CustomerID:** Unique ID for each customer 🆔
* **Gender:** Male 👨 or Female 👩
* **SeniorCitizen:** Are they a senior (1) or not (0)? 👵👴
* **Tenure:** How many months have they been with us? ⏳
* **Contract:** What kind of plan are they on? (Month-to-month 🗓️, One year 📅, Two year 🗓️🗓️)
* **PaymentMethod:** How do they pay? (UPI 📱, Debit Card 💳, Credit card (automatic) 💳🔄)
* **Churn:** Did they leave ("Yes") or stay ("No")? 👋➡️🏠
* **MonthlyCharges:** How much did they pay last month? 💰
* **TotalCharges:** How much have they paid in total? 💸

## Descriptive Analysis Summary 🔍

### Tenure Summary ⏳

| Particulars       | Months |
| :---------------- | :----- |
| Maximum Tenure    | 72     |
| Minimum Tenure    | 1      |
| Average Tenure    | 32     |

### Contract Summary 🗓️

| Contract Type    | Number of Customers |
| :--------------- | :------------------ |
| Month-to-month   | 3875                |
| One year         | 1473                |
| Two year         | 1695                |

### Payment Method Summary 💳

| Contract Type          | Number of Customers |
| :--------------------- | :------------------ |
| UPI                    | 3909                |
| Debit Card             | 1612                |
| Credit card (automatic) | 1522                |

### Customer Churn Summary 👋

| Particulars             | Value   |
| :---------------------- | :------ |
| Total Customers         | 7043    |
| Number of Churned Customers | 1869    |
| Churn Rate              | 26.54%  |

## Key Areas of Analysis 🤔

We focused on understanding who is churning more often by looking at:

* **Gender:** Do men or women leave more? 👨👩
* **Senior Citizens:** Are seniors more likely to churn? 👵👴
* **Tenure:** Does how long someone has been a customer matter? ⏳
* **Contract Type:** Which contract makes people more likely to leave? 🗓️

## Key Findings 💡

Here's what we discovered:

### Churn Rate by Senior Citizen Status 👵👴

| Senior Citizen | Total Customer | Churn Customer | Churn Rate |
| :------------- | :------------- | :------------- | :--------- |
| 0              | 5901           | 1393           | 23.61%     |
| 1              | 1142           | 476            | 41.68%     |

**Insight:** Senior citizens churn way more (41.68%) than non-seniors (23.61%)! 😟

### Churn Rate by Contract Type 🗓️

| Contract Type    | Total Customer | Churn Customer | Churn Rate |
| :--------------- | :------------- | :------------- | :--------- |
| Month-to-month   | 3875           | 1655           | 42.71%     |
| One year         | 1473           | 166            | 11.27%     |
| Two year         | 1695           | 48             | 2.83%      |

**Insight:** Month-to-month contracts have the highest churn (42.71%), while longer contracts see much less churn (Two year: 2.83%)! 🎉

### Churn Rate by Gender 👨👩

| Gender | Total Customer | Churn Customer | Churn Rate |
| :----- | :------------- | :------------- | :--------- |
| Female | 3488           | 939            | 26.92%     |
| Male   | 3555           | 930            | 26.16%     |

**Insight:** Men and women churn at pretty much the same rate. 🤷‍♀️🤷‍♂️

### Churn Rate and Tenure ⏳

**Insight:** The longer someone stays with VFast, the less likely they are to leave! Loyal customers are happy customers! 😊

## Report For Management 📝

1.  **Tenure is Key:** Customers who stick around longer are less likely to churn. Let's keep them happy! 👍
2.  **Gender Doesn't Matter (Much):** Churn rates are similar for both male and female customers. No big differences here. ⚖️
3.  **Contract Length = Loyalty:** Longer contracts mean lower churn. Let's encourage those longer commitments! 🤝
4.  **Senior Citizens Need Attention:** Senior citizens are churning at a higher rate. We need to figure out why and how to better serve them! 🤔👵👴

## Recommendations 💡

To keep more customers, VFast Telecom should think about:

* **Rewarding Loyalty:** Offer special deals or benefits for customers who sign up for longer contracts. 🎁
* **Focusing on Seniors:** Create plans or support specifically for senior citizens to meet their needs. 👵👴📞
* **Engaging New Customers:** Make sure new customers have a great experience from the start to build long-term relationships. 👋😊
* **Digging Deeper:** Do more research to understand *why* seniors and month-to-month customers are churning more. Surveys? Interviews? Let's find out! 🕵️‍♀️

By taking these steps, VFast Telecom can boost customer loyalty and reduce that churn rate! 🎉
