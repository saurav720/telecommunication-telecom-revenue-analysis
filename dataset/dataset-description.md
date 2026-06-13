# Telecom Revenue Analysis – Dataset Description

## 1. Workbook Overview
The Excel dataset used for this project is a workbook-based telecom analytics dataset with the following real scope:
- 7,500 customers
- 12 months of history (Jan–Dec 2024)
- approximately 82,000 billing and usage records

This dataset is designed for Excel pivot analysis and Power BI dashboarding, with a focus on revenue performance, plan behavior, churn, and regional differences.

## 2. Actual Dataset Structure in the Workbook
The workbook contains seven core tables/sheets that should be treated as the primary analytical dataset.

### 2.1 Customer_Master
- Primary key: Customer_ID
- Row count: 7,500
- Key fields: Customer_Type, Region, Status, Tenure_Months
- Purpose: Core customer profile, segmentation, and customer-level analysis

### 2.2 Subscription_Plan
- Primary key: Customer_ID
- Row count: 7,500
- Key fields: Plan_ID, Monthly_Price, Data_Allowance_GB, Plan_Category
- Purpose: Plan mix, pricing, and subscription-level analysis

### 2.3 Usage_Data
- Primary key: Customer_ID + Month
- Row count: approximately 82,800
- Key fields: Voice_Minutes, Data_Usage_GB, Roaming_Usage, OTT_Usage
- Purpose: Monthly consumption behavior and usage-to-revenue analysis

### 2.4 Billing_Revenue
- Primary key: Invoice_ID
- Row count: approximately 82,700
- Key fields: Net_Revenue, Billed_Amount, Discount_Amount, Payment_Status
- Purpose: Revenue, invoicing, payment tracking, and billing quality checks

### 2.5 Churn_Retention
- Primary key: Customer_ID
- Row count: 7,500
- Key fields: Churn_Flag, Churn_Reason, Retention_Offer_Applied
- Purpose: Churn analysis and retention actions

### 2.6 Regional_Geography
- Primary key: Region_ID
- Row count: 20
- Key fields: Region_Name, City, State_Province, Market_Type
- Purpose: Geographic dimension and regional performance analysis

### 2.7 Time_Dimension
- Primary key: Month_ID
- Row count: 12
- Key fields: Month_Name, Quarter, Year, Week_Number
- Purpose: Calendar dimension for monthly and quarterly trend analysis

## 3. Key Relationships for Power BI
Use the following links in the Power BI model view:

- Customer_Master[Customer_ID] -> Subscription_Plan[Customer_ID]
- Customer_Master[Customer_ID] -> Usage_Data[Customer_ID]
- Customer_Master[Customer_ID] -> Billing_Revenue[Customer_ID]
- Customer_Master[Customer_ID] -> Churn_Retention[Customer_ID]
- Customer_Master[City] -> Regional_Geography[City]
- Time_Dimension[Month_Name] -> Usage_Data[Month]
- Time_Dimension[Month_Name] -> Billing_Revenue[Billing_Month]

These relationships are the main structural joins for the analysis.

## 4. Embedded Business Patterns in the Dataset
The workbook already includes built-in patterns that support the revenue analysis objective:
- Revenue leakage: approximately 5% of billing records show usage above plan allowance while being billed at the base rate
- Churn rate: 17.5% overall churn, with higher churn in Prepaid and East/Central regions
- Unpaid invoices: approximately 3% are marked Unpaid and about 8% are Late
- Enterprise discounts: Enterprise and long-tenure customers receive 5%–15% billing discounts
- Regional variance: West and South regions skew toward Metro markets and higher-value plans
- Usage vs billing mismatch: the combined usage, billing, and pricing tables are intended to surface over-usage gaps

## 5. Business Questions This Dataset Supports
This workbook supports the following analytical questions:
- Which customer segments contribute most to revenue?
- Which plans are most profitable and most adopted?
- Are high-usage customers undercharged or underrepresented in revenue?
- Which regions are underperforming or outperforming?
- Which customer groups are most likely to churn?
- Where may revenue leakage be occurring?

## 6. Data Quality Notes
The dataset is structured for direct analysis in Excel and Power BI. For clean reporting, the following should be maintained:
- one unique Customer_ID per customer
- consistent region and plan naming across tables
- standard date formats
- no duplicate records
- valid positive values for revenue, usage, and pricing
- consistent mapping between City, Region, and regional geography

## 7. Expected Outcome
With this workbook structure, the project can move directly into:
- Excel pivot-table analysis
- Power BI dashboard development
- revenue trend analysis
- churn and retention analysis
- regional performance analysis
- revenue leakage investigation
