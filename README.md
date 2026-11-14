# Loan Portfolio & Repayment Analytics Dashboard

An interactive banking loan portfolio and credit risk analysis dashboard built using **Microsoft Power BI** to analyze loan performance, repayment trends, customer demographics, and portfolio risk.

## Project Overview

This project analyzes **37K+ loan records** with a total loan amount of **$422.62M** through a five-page interactive Power BI dashboard.

The objective is to understand loan distribution, repayment performance, customer characteristics, and portfolio trends through interactive visualizations and data-driven insights.

## Key Project Highlights

- Analyzed 37K+ loan records.
- Evaluated a total loan amount of $422.62M.
- Developed a five-page interactive Power BI dashboard.
- Created DAX measures and KPI calculations.
- Analyzed loan status, purpose, credit grades, customer demographics, and home ownership.
- Implemented interactive slicers, drill-downs, bookmarks, and cross-filtering.
- Built a Star Schema data model using one fact table and seven dimension tables.

## Key Performance Indicators

- Total Number of Loans
- Total Loan Amount
- Number of Fully Paid Loans
- Number of Current Loans
- Number of Charged-Off Loans
- Average Loan Amount
- Total Amount from Fully Paid Loans

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| DAX | Measures, calculated tables, and KPIs |
| Power Query | Data transformation and preparation |
| Data Modeling | Establishing table relationships |
| Star Schema | Organizing fact and dimension tables |

## Data Model

The project follows a **Star Schema** with one central fact table connected to seven dimension tables.

**Fact Table**
- Loans

**Dimension Tables**
- Customer
- Home Ownership
- Loan Purpose
- Grade
- Loan Status
- DateDimension
- Verified Status

All seven relationships were individually verified in Power BI with:
- Many-to-One (*:1) cardinality
- Single-direction cross-filtering
- Active relationships

## Dashboard Pages

### 1. Quick Info
Provides an overview of the loan portfolio through key performance indicators, including customer count, total loans, fully paid loans, current loans, charged-off loans, and loan amounts.

### 2. Loans by Status
Analyzes the distribution of loans across Fully Paid, Current, and Charged-Off statuses using interactive visualizations.

### 3. Loans by Different Factors
Explores loan distribution based on customer gender, area, loan purpose, and home ownership.

### 4. Loan Amount by Year & Number of Loans
Analyzes yearly loan trends, installment ranges, and credit grades and sub-grades using interactive slicers and bookmarks.

### 5. Fully Paid Loans
Examines fully paid loan trends by verification status, state, year, month, loan purpose, area, and home ownership.

## Project Structure

- `Loan_Portfolio_Dashboard.pbix` – Power BI dashboard file
- `Loans Data.xlsx` – Loan dataset
- `Date_Dimension_Table.txt` – DAX code for the date dimension
- `Dashboard_Requirements.txt` – Dashboard requirements and planned analysis
- `TD_Bank_Image.png` – Dashboard image asset
