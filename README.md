# 📊 Insurance Claims & Policy Analytics Dashboard

An interactive **Insurance Claims & Policy Analytics Dashboard** developed using **Microsoft Power BI** to analyze insurance policies, customers, premiums, coverage amounts, claims, claim status, age groups, gender and policy types.

The project demonstrates the complete data analytics workflow including **data cleaning, data transformation, data modeling, DAX calculations, KPI development and interactive data visualization**.

---

## 📌 Project Overview

The objective of this project is to transform raw insurance data into an interactive Power BI dashboard that helps users understand:

- Insurance premium performance
- Total insurance coverage
- Claim amount
- Claim ratio
- Loss ratio
- Claim frequency
- Claim status distribution
- Premium contribution by policy type
- Claims by age group
- Customer distribution by gender
- Claims by gender
- Customer and policy-level details

The dashboard includes interactive slicers that allow users to filter and explore the data dynamically.

---

# 🎯 Business Objective

The main objectives of this project are:

1. Analyze the total premium generated.
2. Analyze the total insurance coverage amount.
3. Monitor total claim amount.
4. Calculate claim-related KPIs.
5. Analyze claim status distribution.
6. Compare premium amounts across policy types.
7. Analyze claims across different age groups.
8. Compare customers and claims by gender.
9. Provide interactive filtering capabilities.
10. Present important business insights through data visualization.

---

# 🛠️ Tools & Technologies

The following tools and technologies were used:

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **CSV**
- **GitHub**

---

# 📂 Dataset

The project uses an insurance dataset containing **5,000 records and 15 columns**.

The dataset contains information related to:

- Customers
- Insurance policies
- Premium amounts
- Coverage amounts
- Claims
- Claim dates
- Claim status
- Customer demographics

---

## 📋 Dataset Columns

| Column | Description |
|---|---|
| PolicyNumber | Unique insurance policy number |
| CustomerID | Unique customer identifier |
| Name | Customer name |
| City | Customer city |
| Gender | Customer gender |
| Age | Customer age |
| PolicyType | Type of insurance policy |
| PolicyStartDate | Policy start date |
| PolicyEndDate | Policy end date |
| PremiumAmount | Premium amount paid for the policy |
| CoverageAmount | Insurance coverage amount |
| ClaimNumber | Unique claim identifier |
| ClaimDate | Date of claim |
| ClaimAmount | Amount associated with the claim |
| ClaimStatus | Status of the claim |

---

# 🔄 Project Workflow

The project follows the complete data analytics workflow:

```text
Raw Insurance Dataset
        ↓
Data Understanding
        ↓
Data Quality Checks
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Dashboard Design
        ↓
Interactive Analysis
        ↓
Business Insights
```

---

# 🧹 Data Cleaning & Transformation

The raw dataset was prepared using **Power Query**.

The following data preparation activities were performed:

- Reviewed the dataset structure.
- Checked the number of rows and columns.
- Checked for duplicate records.
- Checked missing values.
- Reviewed column data types.
- Converted date fields into appropriate Date data types.
- Validated numerical fields.
- Reviewed categorical fields.
- Checked claim-related fields.
- Prepared the dataset for Power BI analysis.

### Data Quality Summary

| Data Quality Check | Result |
|---|---:|
| Total Records | 5,000 |
| Total Columns | 15 |
| Duplicate Records | 0 |
| Age Range | 21–75 |
| Policy Types | 3 |
| Claim Status Categories | 3 |

Missing values, particularly in claim-related date fields, were reviewed as part of the data-cleaning process.

---

# 🏗️ Data Modeling

The cleaned dataset was loaded into Power BI and prepared for analysis.

The model supports analysis across:

- Customers
- Policies
- Premiums
- Coverage
- Claims
- Claim status
- Gender
- Age groups
- Policy types


---

# 📐 DAX & KPI Development

DAX measures were created to calculate important insurance KPIs.

The major measures include:

- Total Premium Amount
- Total Coverage Amount
- Total Claim Amount
- Claim Ratio
- Loss Ratio
- Claim Frequency
- Total Claims
- Total Policies
- Total Customers
- Average Premium
- Average Coverage
- Average Claim Amount


---

# 📊 Dashboard KPIs

The dashboard contains the following key performance indicators:

| KPI | Value |
|---|---:|
| Premium Amount | 4.38M |
| Coverage Amount | 300.22M |
| Claim Amount | 19.37M |
| Claim Ratio | 4.42 |
| Loss Ratio | 1.48 |
| Claim Frequency | 1.00 |

These KPIs provide a high-level overview of the insurance portfolio.

---

# 📈 Dashboard Visualizations

The dashboard contains multiple interactive visualizations.

## 1. Customer by Gender

A donut chart showing the distribution of customers based on gender.

The dashboard shows a relatively balanced distribution between male and female customers.

---

## 2. Claim Status

A bar chart showing the distribution of claims by status:

- Rejected
- Pending
- Settled

Rejected claims represent the largest category in the displayed dashboard.

---

## 3. Premium Amount by Policy Type

A comparison of premium amounts across:

- Auto
- Health
- Travel

This visual helps identify the policy categories contributing the most premium.

---

## 4. Claim by Age Group

Claims are categorized into:

- Young
- Adult
- Elder

This allows comparison of claim volumes across different customer age groups.

---

## 5. Claim by Gender

A column chart comparing claim counts between:

- Male
- Female

This helps identify differences in claim volume between customer genders.

---

## 6. Detailed Policy Table

The dashboard includes a detailed table containing fields such as:

- Name
- Gender
- Age
- City
- Policy Number
- Premium Amount
- Coverage Amount

This allows users to inspect individual policy records.

---

# 🎛️ Interactive Filters

The dashboard includes slicers for:

- Claim Number
- Customer ID
- Policy Number

These slicers allow users to dynamically filter the dashboard and analyze specific customers, policies or claims.

---

# 🔍 Key Business Insights

The dashboard provides the following high-level insights:

### Premium Performance

The total premium amount in the dataset is approximately **4.38M**.

### Coverage

The total insurance coverage represented in the dataset is approximately **300.22M**.

### Claims

The total claim amount is approximately **19.37M**.

### Claim Status

Rejected claims represent the largest claim-status category in the dashboard, followed by pending and settled claims.

### Policy Type

Auto, Health and Travel are the three major policy categories. Premium amounts can be compared across these categories to understand their contribution to the overall portfolio.

### Customer Demographics

The customer distribution by gender is relatively balanced.

### Age Group

Adult customers represent the highest claim group in the dashboard, followed by Elder and Young customers.

---

# 💡 Business Value

The dashboard can help insurance stakeholders:

- Monitor premium performance.
- Monitor total claim amounts.
- Understand claim distribution.
- Compare policy types.
- Analyze customer demographics.
- Identify claim patterns.
- Monitor insurance KPIs.
- Analyze policy-level information.
- Support data-driven decision-making.

---

# ❓ Business Questions Answered

The dashboard is designed to answer questions such as:

1. What is the total premium generated?
2. What is the total insurance coverage?
3. What is the total claim amount?
4. What is the claim ratio?
5. What is the loss ratio?
6. What is the claim frequency?
7. Which claim status has the highest number of claims?
8. Which policy type generates the highest premium?
9. Which age group has the highest number of claims?
10. How are customers distributed by gender?
11. How do claims differ by gender?
12. How does the dashboard change when a customer, claim or policy is selected?

---

# 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX
- KPI Development
- Data Visualization
- Dashboard Development
- Business Analysis
- Interactive Reporting
- GitHub Project Documentation

---


# ⭐ Project Highlights

**5,000+ insurance records analyzed**

**15 data fields**

**Power Query data cleaning**

**DAX-based KPI calculations**

**Interactive Power BI dashboard**

**Customer, policy and claim analysis**

**Business-focused insights**
