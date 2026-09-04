# Insurance Claims & Policy Analytics Dashboard

## 📊 Project Overview

This project is an interactive Insurance Analytics Dashboard developed using Microsoft Power BI.

The objective of this project is to analyze insurance policy performance, premium collections, coverage amounts, claim amounts, claim status, customer demographics, and policy types.

The dashboard enables users to interactively explore insurance data using filters and slicers and identify important business trends and patterns.

---

## 🎯 Business Objective

The main objectives of this project are:

- Analyze total premium collected
- Analyze total insurance coverage
- Track total claim amount
- Monitor claim ratio
- Monitor loss ratio
- Analyze claim frequency
- Understand claim status distribution
- Compare premium amounts across policy types
- Analyze claims across different age groups
- Compare customers and claims by gender
- Provide an interactive dashboard for business analysis

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Excel/CSV
- GitHub

---

## 📁 Dataset

The dataset contains insurance policy and claim information.

### Dataset Size

- Records: 5,000
- Columns: 15

### Main Columns

| Column | Description |
|---|---|
| PolicyNumber | Unique policy identifier |
| CustomerID | Customer identifier |
| Name | Customer name |
| City | Customer city |
| Gender | Customer gender |
| Age | Customer age |
| PolicyType | Type of insurance policy |
| PolicyStartDate | Policy start date |
| PolicyEndDate | Policy end date |
| PremiumAmount | Premium paid for the policy |
| CoverageAmount | Insurance coverage amount |
| ClaimNumber | Claim identifier |
| ClaimDate | Date of claim |
| ClaimAmount | Amount claimed |
| ClaimStatus | Current claim status |

---

## 🧹 Data Cleaning

The dataset was cleaned and prepared using Power Query before creating the dashboard.

The major data preparation steps included:

- Checked for duplicate records
- Checked missing values
- Corrected data types
- Converted date columns into proper Date format
- Validated numerical columns
- Checked categorical values
- Reviewed claim-related missing values
- Standardized fields required for analysis
- Prepared the dataset for Power BI data modeling

---

## 🏗️ Data Modeling

The cleaned dataset was loaded into Power BI and prepared for analysis.

The data model was designed to support:

- Policy analysis
- Customer analysis
- Claim analysis
- Premium analysis
- Coverage analysis
- Demographic analysis

Relationships and fields were reviewed to ensure accurate filtering and aggregation across dashboard visuals.

---

## 📐 DAX Measures

Several DAX measures were created to calculate important business KPIs.

### Total Premium

```DAX
Total Premium =
SUM(Insurance_data[PremiumAmount])

Total Coverage =
SUM(Insurance_data[CoverageAmount])

Total Claim Amount =
SUM(Insurance_data[ClaimAmount])

Claim Ratio % =
DIVIDE(SUM(Insurance_data[ClaimAmount]),SUM(Insurance_data[PremiumAmount]) )

Loss Ratio % =
DIVIDE(CALCULATE(SUM(Insurance_data[ClaimAmount]),Insurance_data[ClaimStatus]="settled"),SUM(Insurance_data[PremiumAmount]),0)

Claim Frequency % =
DIVIDE(DISTINCTCOUNT(Insurance_data[ClaimNumber]),DISTINCTCOUNT(Insurance_data[PolicyNumber]),0)
