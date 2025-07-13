# Bank Loan Report Dashboard

## Project Overview

The **Bank Loan Report Dashboard** is a comprehensive data analysis project aimed at visualizing and monitoring key metrics related to loan applications, funding, repayments, and customer profiles for a financial institution.
This project provides clear insights into loan performance, customer behavior, and financial KPIs through interactive dashboards.

## Tools & Technologies Used

* **MySQL** – For data extraction, data cleaning, and performing SQL queries to compute business metrics.
* **Excel** – For initial data preprocessing and data understanding.
* **Tableau** – For building interactive and visually appealing dashboards.

## Dataset

The dataset used in this project is a **bank's financial loan dataset** containing information such as:

* Loan ID
* Loan Purpose
* Home Ownership Status
* Loan Amount and Funded Amount
* Interest Rate (Int Rate)
* Debt-to-Income Ratio (DTI)
* Loan Status (Fully Paid, Charged Off, Current)
* Issue Date, Installments, and Total Payment received
  (Source: `financial_loan.csv`)

---

## Key Features

### 1️⃣ **Summary Dashboard**

* **Total Loan Applications**: 38.6K
* **Total Funded Amount**: \$435.8M
* **Total Amount Received**: \$473.1M
* **Average Interest Rate**: 12.0%
* **Average Debt-to-Income (DTI)**: 13.3%
* **Good Loan Percentage**: 86.2% (Fully Paid / Current)
* **Bad Loan Percentage**: 13.8% (Charged Off)

**Loan Status Analysis**:

| Loan Status | Applications | Amount Received | Funded Amount |
| ----------- | ------------ | --------------- | ------------- |
| Charged Off | 5.3K         | \$37.3M         | \$65.5M       |
| Current     | 1.1K         | \$24.2M         | \$18.9M       |
| Fully Paid  | 32.1K        | \$411.6M        | \$351.4M      |

---

### 2️⃣ **Overview Dashboard**

* **Loan Trends**: Total funded amount by month showing consistent growth.

* **State-wise Distribution**: Visualizing total funded amounts across different states.

* **Loan Terms**: 62.66% loans are for 36 months, and 37.34% for 60 months.

* **Purpose-wise Analysis**:

  * Debt Consolidation: \$232.4M
  * Credit Card: \$58.8M
  * Home Improvement, Small Business, Car, Wedding, Major Purchase, etc.

* **Home Ownership Analysis**:

  * MORTGAGE: \$219.3M
  * RENT: \$185.7M
  * OWN: Remaining proportion

* **Employee Length Analysis**: Insights into loan distribution based on employment length.

---

### 3️⃣ **Details Dashboard**

Provides a granular, transaction-level view of:

* Loan IDs
* Purpose of Loan
* Home Ownership Status
* Loan Grades and Sub-Grades
* Loan Issue Dates
* Loan Amounts, Installments, Total Payment

---

## SQL Queries Performed

Key SQL operations include:

* Calculating total applications, funded amounts, and collections
* Segmenting data by loan status (Good/Bad Loans)
* Generating month-over-month (MoM) and month-to-date (MTD) performance metrics
* Analyzing customer behavior by purpose, state, employee length, term, and home ownership

You can find the SQL queries [**here**] .

---

## Business Insights

* The majority of loans are for **debt consolidation** and **credit card refinancing**.
* **MORTGAGE** owners and **RENTERS** are the major loan seekers.
* Most loans are of **36-month terms**, indicating preference for short-term repayment plans.
* The loan default rate is around **13.8%**, while the good loan rate is **86.2%**, suggesting healthy loan management.
* The company earns significantly more in **total payments collected** than the funded amounts, indicating profitable interest returns.

---

## Project Highlights

* **End-to-End Data Pipeline**: From SQL querying and data cleaning in Excel to Tableau visualization.
* **KPI Tracking**: Real-time insights into business performance metrics.
* **Data-Driven Decision Making**: Helps banks identify risk areas and optimize loan policies.

---

## Repository Structure

```
|-- financial_loan.csv         # Dataset
|-- Bank_Loan SQL queries.docx # SQL queries
|-- Dashboard_1(Summary).jpg   # Summary dashboard
|-- Dashboard_2(Overview).jpg  # Overview dashboard
|-- Dashboard_3(Details).jpg   # Detailed dashboard
|-- README.md                  # Project documentation
```

---

## Conclusion

This **Bank Loan Report project** provides valuable insights into loan management, repayment trends, and customer segmentation. It is a powerful tool for financial analysts and bank management to monitor performance and make informed decisions.
