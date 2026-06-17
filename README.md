# telecommunication

# Telecom Revenue Analysis Project

## Project Overview

This project analyzes telecom customer revenue, usage behavior, subscription plans, churn patterns, and regional performance using Excel and Power BI.

The dataset contains approximately 7,500 customers, 12 months of historical data (January–December 2024), and around 82,000 billing and usage records. The objective is to identify revenue opportunities, understand customer behavior, detect revenue leakage, and support business decision-making through data visualization and reporting.

---

# Business Objective

The primary goals of this project are:

- Analyze revenue performance across customer segments
- Evaluate subscription plan adoption and profitability
- Identify potential revenue leakage
- Understand churn behavior and retention effectiveness
- Compare regional performance
- Monitor billing and payment trends
- Build interactive dashboards for business stakeholders

---

# Dataset Overview

## Total Scope

| Metric          | Value                     |
| --------------- | ------------------------- |
| Customers       | 7,500                     |
| Time Period     | Jan 2024 – Dec 2024      |
| Usage Records   | ~82,800                   |
| Billing Records | ~82,700                   |
| Regions         | 20                        |
| Dataset Type    | Telecom Revenue Analytics |

---

# Data Model

The workbook contains seven core tables.

## 1. Customer_Master

Customer profile and segmentation information.

### Key Columns

- Customer_ID
- Customer_Type
- Region
- Status
- Tenure_Months

### Purpose

Used for:

- Customer segmentation
- Revenue contribution analysis
- Tenure analysis
- Customer status tracking

---

## 2. Subscription_Plan

Customer subscription details.

### Key Columns

- Customer_ID
- Plan_ID
- Monthly_Price
- Data_Allowance_GB
- Plan_Category

### Purpose

Used for:

- Plan adoption analysis
- Pricing analysis
- Plan profitability evaluation

---

## 3. Usage_Data

Monthly customer usage information.

### Key Columns

- Customer_ID
- Month
- Voice_Minutes
- Data_Usage_GB
- Roaming_Usage
- OTT_Usage

### Purpose

Used for:

- Usage trend analysis
- Over-usage detection
- Revenue leakage identification

---

## 4. Billing_Revenue

Billing and payment records.

### Key Columns

- Invoice_ID
- Customer_ID
- Billing_Month
- Billed_Amount
- Discount_Amount
- Net_Revenue
- Payment_Status

### Purpose

Used for:

- Revenue analysis
- Billing performance
- Payment tracking
- Revenue trend reporting

---

## 5. Churn_Retention

Customer churn information.

### Key Columns

- Customer_ID
- Churn_Flag
- Churn_Reason
- Retention_Offer_Applied

### Purpose

Used for:

- Churn analysis
- Retention program evaluation
- Customer risk identification

---

## 6. Regional_Geography

Regional dimension table.

### Key Columns

- Region_ID
- Region_Name
- City
- State_Province
- Market_Type

### Purpose

Used for:

- Geographic reporting
- Regional performance comparison
- Market analysis

---

## 7. Time_Dimension

Calendar dimension.

### Key Columns

- Month_ID
- Month_Name
- Quarter
- Year
- Week_Number

### Purpose

Used for:

- Time intelligence
- Monthly trends
- Quarterly reporting

---

# Power BI Data Model Relationships

Create the following relationships:

Customer_Master[Customer_ID]
→ Subscription_Plan[Customer_ID]

Customer_Master[Customer_ID]
→ Usage_Data[Customer_ID]

Customer_Master[Customer_ID]
→ Billing_Revenue[Customer_ID]

Customer_Master[Customer_ID]
→ Churn_Retention[Customer_ID]

Customer_Master[City]
→ Regional_Geography[City]

Time_Dimension[Month_Name]
→ Usage_Data[Month]

Time_Dimension[Month_Name]
→ Billing_Revenue[Billing_Month]

---

# Business Rules Embedded in Dataset

## Revenue Leakage

Approximately 5% of customers exceed plan allowance while being billed at the standard base rate.

### Business Impact

Potential lost revenue from unbilled over-usage.

---

## Churn Pattern

Overall churn rate:

17.5%

Higher churn observed in:

- Prepaid customers
- East Region
- Central Region

---

## Payment Status

Approximate distribution:

- Paid: 89%
- Late: 8%
- Unpaid: 3%

### Business Impact

Monitoring collection efficiency and cash flow.

---

## Enterprise Discounts

Enterprise and long-tenure customers receive:

- 5%–15% discounts

### Business Impact

Revenue reduction versus customer retention benefits.

---

## Regional Performance Variance

Higher-value customers are concentrated in:

- West Region
- South Region

These regions contain a larger share of Metro markets and premium plans.

---

# Key Business Questions

The project answers the following questions:

### Revenue Analysis

- Which customer segments generate the most revenue?
- What is the monthly revenue trend?
- Which regions contribute the highest revenue?

### Plan Analysis

- Which plans are most popular?
- Which plans generate the highest profit?
- Are customers exceeding their plan limits?

### Customer Analysis

- What is the revenue contribution by customer type?
- How does tenure impact revenue?

### Churn Analysis

- Which customer groups churn the most?
- What are the major churn reasons?
- Are retention offers reducing churn?

### Revenue Leakage Analysis

- Which customers exceed plan limits?
- How much potential revenue is lost?
- Which plans are most affected?

---

# Suggested Power BI KPIs

Create KPI Cards for:

- Total Revenue
- Total Customers
- Active Customers
- Churn Rate
- Average Revenue Per User (ARPU)
- Total Usage (GB)
- Revenue Leakage Amount
- Unpaid Revenue
- Average Discount %

---

# Recommended Dashboard Pages

## Executive Summary

- Revenue KPI
- Customer KPI
- Churn KPI
- Revenue Trend

---

## Revenue Analysis

- Monthly Revenue Trend
- Revenue by Region
- Revenue by Customer Type
- Revenue by Plan Category

---

## Customer & Usage Analysis

- Data Usage Trend
- Voice Usage Trend
- OTT Usage Analysis
- High Usage Customers

---

## Churn Analysis

- Churn Rate by Region
- Churn by Customer Type
- Churn Reasons
- Retention Offer Impact

---

## Revenue Leakage Analysis

- Usage vs Plan Allowance
- Leakage Amount
- Affected Customers
- Leakage by Region

---

# Data Quality Requirements

Before analysis ensure:

- Unique Customer_ID values
- No duplicate records
- Consistent plan naming
- Consistent region naming
- Valid positive revenue values
- Standard date formats
- Correct city-to-region mapping

---

# Tools Used

- Microsoft Excel
- Power Query
- Power Pivot
- Power BI Desktop
- DAX
- Pivot Tables

---

# Expected Deliverables

- Cleaned analytical dataset
- Excel pivot-table reports
- Interactive Power BI dashboard
- Revenue performance insights
- Churn analysis report
- Revenue leakage report
- Regional performance dashboard

---

# Author

Saurav Singh Mandrawal

Telecom Revenue Analysis Project
Power BI & Data Analytics Portfolio Project
