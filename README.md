# VFast Telecom Customer Churn Analysis 📊

## 🚀 Overview

VFast Telecom, a leading telecom service provider in **Varanasi 🇮🇳**, has seen a rise in customer churn for its broadband services. This analysis aims to uncover the **reasons behind customer churn** and provide actionable insights to help retain customers and reduce churn. 🤝

---

## 💾 Dataset

We used the `Data_CustomerChurn` dataset which contains the following fields:

| Column            | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `CustomerID`      | Unique ID for each customer 🆔                                               |
| `Gender`          | Gender of customer: Male 👨 or Female 👩                                     |
| `SeniorCitizen`   | Indicates if the customer is a senior (1) or not (0) 👵👴                   |
| `Tenure`          | Duration of association in months ⏳                                         |
| `Contract`        | Customer contract type: Month-to-month 🗓️, One year 📅, Two year 🗓️🗓️     |
| `PaymentMethod`   | UPI 📱, Debit Card 💳, Credit card (automatic) 💳🔄                         |
| `Churn`           | Did they leave ("Yes") or stay ("No")? 👋➡️🏠                               |
| `MonthlyCharges`  | Last month's charges 💰                                                    |
| `TotalCharges`    | Total charges over the entire tenure 💸                                     |

---

## 🔧 Step-by-Step Tasks & Excel Tab Setup 🧾

### 🔍 **Task 1: Descriptive Analysis**
1. ➕ **Add a new tab** in Excel.
2. ✏️ **Rename it** `Descriptive Analysis`.
3. 📊 Perform descriptive analysis using formulas:
   - `=AVERAGE()`, `=MAX()`, `=MIN()`, `=MEDIAN()`, `=STDEV.P()` for numeric columns like `Tenure`, `MonthlyCharges`, `TotalCharges`.
   - `=COUNTIF()` to get counts by `Gender`, `Churn`, `Contract`, etc.
4. 📈 Add basic summary tables

---

### 🧮 **Task 2: Tenure-wise Active/Inactive**
1. ➕ Add a new tab, rename it `Tenure_Active/Inactive`.
2. 🔄 Create a pivot table:
   - Rows: `Tenure`
   - Columns: `Churn`
   - Values: `CustomerID` (count)
3. 🧠 This will show the number of active and inactive customers per tenure group.

---

### 📦 **Task 3: Plan-wise Churn Rate**
1. ➕ Add a tab, rename it `Plan_Churn`.
2. 🗂️ Create a pivot:
   - Rows: `Contract`
   - Columns: `Churn`
   - Values: `CustomerID` (count)
3. ➗ Add a formula to calculate:
4. 📉 Optional: Add bar chart for visual impact.

---

### ⏳ **Task 4: Tenure-wise Churn Rate**
1. ➕ Add a tab called `Tenure_Churn`.
2. 📋 Create a pivot table:
- Rows: `Tenure`
- Columns: `Churn`
- Values: `CustomerID` (count)
3. ➗ Use a formula to compute churn rate.
4. 📊 Optional: Add a line chart to show the churn trend over tenure.

---

### 🏙️ **Task 5: City-wise Churn Rate**
1. ➕ Add a tab called `City_Churn`.
2. 🧱 Create pivot:
- Rows: `City`
- Columns: `Churn`
- Values: Count of `CustomerID`
3. 📊 Compute churn rate and visualize using a bar chart.

---

### 🚻 **Task 6: Gender-wise Churn Rate**
1. ➕ Add a tab, rename it `Gender_Churn`.
2. ⚖️ Pivot setup:
- Rows: `Gender`
- Columns: `Churn`
- Values: Count of `CustomerID`
3. ➗ Calculate churn rate using standard formula.

---

### 📊 **Task 7: Dashboard**
1. ➕ Add a tab called `Dashboard`.
2. 🧩 Combine summary KPIs, charts, slicers for interactivity.
3. 🎨 Use visual tools like conditional formatting and layout grouping to enhance presentation.

---

### 📘 **Task 8: Insights**
1. ➕ Add a tab called `Insights`.
2. 📝 Summarize findings for stakeholders:
- Key patterns
- Risks
- Opportunities
- Actionable steps
3. 📌 Use bullets, bold highlights, and emojis for readability.

---

## 💡 Key Findings

### 👵👴 Churn Rate by Senior Citizen

| Senior Citizen | Total Customers | Churned Customers | Churn Rate |
|----------------|------------------|--------------------|------------|
| 0              | 5901             | 1393               | 23.61%     |
| 1              | 1142             | 476                | 41.68%     |

> **Insight:** Senior citizens churn significantly more than others 😟

---

### 🗓️ Churn Rate by Contract Type

| Contract Type    | Total Customers | Churned Customers | Churn Rate |
|------------------|------------------|--------------------|------------|
| Month-to-month   | 3875             | 1655               | 42.71%     |
| One year         | 1473             | 166                | 11.27%     |
| Two year         | 1695             | 48                 | 2.83%      |

> **Insight:** Longer-term contracts = lower churn 🎯

---

### 🚻 Churn Rate by Gender

| Gender | Total Customers | Churned Customers | Churn Rate |
|--------|------------------|--------------------|------------|
| Female | 3488             | 939                | 26.92%     |
| Male   | 3555             | 930                | 26.16%     |

> **Insight:** Churn is fairly even across genders 🤷

---

### ⏳ Tenure vs. Churn

> **Insight:** Longer-tenure customers are more loyal and less likely to churn 😊

---

## 📝 Report For Management

1. ✅ **Tenure is Critical**: Customers who stay longer are less likely to churn.
2. ⚖️ **Gender Has Minimal Impact**: Churn is nearly equal among male and female customers.
3. 🛡️ **Promote Long-Term Contracts**: These see the least churn and highest retention.
4. 👵 **Senior Citizens Are Vulnerable**: They require more engagement and personalized support.

---

## 💡 Recommendations

- 📢 Offer incentives for long-term contracts.
- 💬 Improve customer care for senior citizens.
- 🎁 Build loyalty programs to retain customers longer.
- 🔍 Monitor early churn signs in new customers.

---

## 📂 Excel Tabs Structure

| Tab Name               | Description                            |
|------------------------|----------------------------------------|
| `Data`                 | Raw customer data                      |
| `Descriptive Analysis` | Overall stats and summaries            |
| `Tenure_Active/Inactive` | Tenure-wise customer status          |
| `Plan_Churn`           | Contract type-based churn analysis     |
| `Tenure_Churn`         | Churn rate across tenure               |
| `City_Churn`           | City-wise churn stats                  |
| `Gender_Churn`         | Gender-based churn analysis            |
| `Dashboard`            | Visual dashboard for key indicators    |
| `Insights`             | Written report & key takeaways         |

---

📢 *Built with 💙 by your data analytics team!*
