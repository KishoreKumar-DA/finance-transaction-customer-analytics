# Finance Transaction & Customer Analytics

<img width="1477" height="835" alt="image" src="https://github.com/user-attachments/assets/bb9a315f-f4ec-43b9-b079-ec756493283d" />

<img width="1477" height="835" alt="image" src="https://github.com/user-attachments/assets/2619322a-4f2e-42ea-8a99-96f112719462" />


## Project Overview

This project is an end-to-end **Finance Transaction & Customer Analytics** solution built using Microsoft Power BI.

The project analyzes financial transactions and customer information to understand transaction activity, financial performance, customer segments, transaction types, geographic distribution, transaction status, fees, taxes, and other customer and transaction patterns.

The objective is to transform structured customer and transaction data into an interactive dashboard that enables users to explore financial performance and transaction-level details.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- Data Cleaning & Transformation
- Data Visualization
- KPI Analysis

---

## 📊 Dataset

The project uses two datasets:

### Customers

Contains customer-level information including:

- Customer ID
- First Name
- Second Name
- Gender
- Date of Birth
- City
- State
- Occupation
- Customer Segment
- Annual Income
- Join Date

### Finance Transactions

Contains transaction-level information including:

- Transaction ID
- Transaction Date
- Account ID
- Customer ID
- Transaction Type
- Channel
- Merchant Category
- Amount
- Fee Amount
- Tax Amount
- Currency
- Transaction Status
- Fraud Indicator
- Risk Score
- Reference Number

### Dataset Size

- **5,000 customers**
- **50,069 financial transactions**

---

# 📈 Power BI Dashboard

The Power BI report contains two interactive pages.

## Page 1: Overview Analysis

The Overview Analysis page provides a high-level view of financial transaction activity.

### Key KPIs

- Total Amount
- Total Transactions
- Average Transaction
- Total Fees
- Total Tax

### Visual Analysis

- Total Transactions by Month
- Total Transactions by Transaction Status
- Total Transactions by Customer Segment
- Total Transactions by State
- Transaction Type Analysis
- Total Transactions by Gender

### Filters

Users can dynamically filter the dashboard using:

- Year
- Occupation
- Category

The dashboard also includes a dynamic metric selection for transaction analysis.

---

## Page 2: Transaction Analysis

The Transaction Analysis page provides detailed transaction-level reporting.

The table includes:

- Transaction ID
- Transaction Date
- Customer Name
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- State
- Total Amount
- Total Fees
- Total Tax

Users can apply the available filters to investigate individual transactions and analyze transaction patterns.

---

# 🔍 Key Analysis Areas

The dashboard enables analysis across several business dimensions:

### Transaction Performance

Analyzes transaction volume and monetary value across different periods and transaction types.

### Customer Segmentation

Examines transaction activity across customer segments such as:

- Retail
- Premium
- SME
- Corporate
- Wealth

### Geographic Analysis

Analyzes transaction distribution across different states.

### Transaction Types

Compares transaction activity and financial values across different transaction types.

### Transaction Status

Provides visibility into transaction outcomes including:

- Success
- Failed
- Pending

### Financial Charges

Analyzes fees and taxes associated with financial transactions.

### Customer Demographics

Provides transaction-level analysis by gender and occupation.

---

# 💡 Business Questions Addressed

The dashboard helps answer questions such as:

- How many transactions are processed?
- What is the total transaction amount?
- What is the average transaction value?
- How do transaction volumes change over time?
- Which customer segments generate the highest transaction activity?
- Which states have higher transaction volumes?
- Which transaction types contribute the most transaction value?
- What proportion of transactions are successful, failed, or pending?
- How do fees and taxes vary across transaction types?
- How can individual transactions be investigated using interactive filters?

---

# 📌 Project Workflow

```text
Customer & Transaction Data
            ↓
      Data Preparation
            ↓
       Power Query
            ↓
      Data Modeling
            ↓
          DAX
            ↓
    KPI & Visual Analysis
            ↓
    Interactive Dashboard
            ↓
    Business Insights
---
👤 Author

Kishore Kumar

Data Analyst | Power BI | SQL | Excel | Python
