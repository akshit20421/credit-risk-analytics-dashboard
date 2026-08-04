# Credit Risk Analytics Dashboard

## Overview

This project presents a comprehensive 4-page Credit Risk Analytics Dashboard built in Power BI to analyze borrower behavior, portfolio performance, default risk drivers, and expected credit loss (ECL).

The dashboard enables risk analysts and lending teams to identify high-risk borrower segments, understand key factors influencing defaults, and monitor overall portfolio health through interactive visualizations and drill-down reporting.

---

## Business Problem

Financial institutions need to effectively assess borrower risk, monitor portfolio quality, and minimize potential credit losses.

This dashboard addresses critical business questions:

- Which borrower segments exhibit the highest default risk?
- How does credit score impact default probability?
- Does debt burden increase default risk?
- Which loan purposes contribute most to portfolio risk?
- What factors drive borrower defaults?
- What is the estimated Expected Credit Loss (ECL) across the portfolio?

---

## Dataset

**Records:** 255,347 loan applications

### Key Features

- Age
- Income
- Credit Score
- Employment Type
- Education
- Loan Purpose
- Interest Rate
- Loan Term
- Debt-to-Income Ratio (DTI)
- Default Flag

---

## Dashboard Pages

### Page 1 – Executive Summary

Provides a portfolio-level overview of lending performance.

**Visuals**
- Total Loans
- Total Defaults
- Default Rate
- Average Credit Score
- Total Loan Book
- Risk Band Distribution
- Default Rate by Loan Purpose
- Default Rate by Employment Type

**Key Findings**
- Business loans exhibit the highest default rate.
- Unemployed borrowers demonstrate elevated risk.
- Very High Risk borrowers represent the largest risk segment.
<img width="1332" height="741" alt="Screenshot 2026-08-04 215507" src="https://github.com/user-attachments/assets/dc5e6fd6-73b9-415b-bc78-8deddf2363b5" />

---

### Page 2 – Borrower Risk Segmentation

Analyzes borrower demographics and financial characteristics.

**Visuals**
- Default Rate by Age Band
- Default Rate by Income Band
- Default Rate by Education
- Risk Band Performance Matrix

**Key Findings**
- Younger borrowers show significantly higher default rates.
- Lower-income borrowers demonstrate elevated risk.
- Higher educational attainment is associated with lower default rates.

---

### Page 3 – Credit Score & DTI Analysis

Examines key credit risk drivers.

**Visuals**
- Default Rate by Credit Score Bucket
- Default Rate by DTI Band
- Default Rate by Interest Rate Band
- Default Rate by Loan Term

**Key Findings**
- Default rates decline as credit scores improve.
- Higher DTI ratios are associated with higher default risk.
- High-interest loans exhibit significantly elevated default rates.
- Loan term has limited impact on portfolio default rates.

---

### Page 4 – Interactive Portfolio Explorer

Enables dynamic portfolio exploration through interactive filtering.

**Visuals**
- Risk Segment Matrix
- Employment Risk Analysis
- Interactive Slicers
- Portfolio Drill-Down Views

**Filters**
- Risk Band
- Employment Type
- Loan Purpose
- Loan Term

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|------|------|
| Total Loans | 255,347 |
| Total Defaults | 29,653 |
| Default Rate | 11.61% |
| Average Credit Score | 574 |
| Total Loan Book | 33 Billion |
| Estimated ECL | 1.61 Billion |

---

## Key Insights

- Business loans show the highest default rate at 12.33%.
- Unemployed borrowers default significantly more often than full-time employees.
- Borrowers aged 18–30 exhibit nearly four times the default rate of borrowers aged 60–70.
- Lower-income borrowers display substantially higher default risk.
- Credit score is a strong predictor of default probability.
- Borrowers with DTI above 60% demonstrate elevated default risk.
- Loans carrying interest rates above 20% show nearly three times the default rate of low-interest loans.
- The Very High Risk segment contributes disproportionately to portfolio risk exposure.

---

## Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization
- Credit Risk Analytics
- Portfolio Analytics

---

## Project Structure

Credit-Risk-Analytics-Dashboard/
│
├── Dashboard.pbix
├── README.md
└── dataset/
└── loan_default.csv

---

## Resume Description

Built a 4-page Credit Risk Analytics Dashboard in Power BI analyzing 255K+ loan records, borrower segmentation, default risk drivers, Expected Credit Loss (ECL), credit score behavior, and portfolio performance using DAX, Power Query, and interactive reporting.

---

## Author

Akshit Gupta

M.Sc. Operational Research, Hansraj College, University of Delhi
