# Telecom Revenue Analysis – Dataset Description

## 1. Objective
To resolve the project problem statement, the dataset must help the team understand why telecom revenue is underperforming and where opportunities for improvement exist. The analysis should focus on:
- revenue contribution by customer segment
- subscription plan performance
- churn and retention patterns
- regional performance differences
- usage versus billing alignment
- potential revenue leakage

## 2. Recommended Dataset Structure
The most useful dataset for this project is a combined business dataset made of the following core tables.

### 2.1 Customer Master Data
This table identifies the customer base and supports segment analysis.

Recommended fields:
- Customer_ID
- Customer_Name (optional)
- Age_Group
- Gender
- Customer_Type (Prepaid / Postpaid / Enterprise / Consumer)
- Tenure_Months
- Registration_Date
- Region
- City / District
- Status (Active / Inactive / Churned)

Why this matters:
- helps identify high-value and at-risk customer groups
- supports ARPU, CLV, and churn analysis

### 2.2 Subscription and Plan Data
This table explains the product mix and pricing structure.

Recommended fields:
- Customer_ID
- Plan_ID
- Plan_Name
- Plan_Category (Basic / Standard / Premium / Bundle)
- Monthly_Price
- Data_Allowance
- Voice_Allowance
- SMS_Allowance
- Add_Ons
- Plan_Start_Date
- Plan_End_Date
- Current_Plan_Flag

Why this matters:
- reveals which plans contribute most to revenue
- identifies low-performing or under-adopted plans

### 2.3 Usage Data
This table shows how customers actually consume telecom services.

Recommended fields:
- Customer_ID
- Month
- Voice_Minutes
- Data_Usage_GB
- SMS_Count
- Roaming_Usage
- OTT_Usage (if applicable)
- Network_Usage_Events

Why this matters:
- highlights usage-to-revenue mismatch
- identifies upsell or cross-sell opportunities
- helps detect possible billing or revenue leakage issues

### 2.4 Billing and Revenue Data
This is the most critical dataset for the financial analysis.

Recommended fields:
- Customer_ID
- Billing_Month
- Invoice_ID
- Service_Type
- Charge_Type (Voice / Data / Bundle / Add-On / Equipment)
- Billed_Amount
- Discount_Amount
- Tax_Amount
- Net_Revenue
- Payment_Status
- Payment_Date

Why this matters:
- forms the base for total revenue, ARPU, and growth analysis
- supports detection of missing or under-billed revenue

### 2.5 Churn and Retention Data
This table helps measure customer loss and retention outcomes.

Recommended fields:
- Customer_ID
- Churn_Flag
- Churn_Date
- Churn_Reason
- Last_Active_Month
- Contract_End_Date
- Retention_Offer_Applied
- Previous_Plan_ID

Why this matters:
- essential for churn analysis by plan, segment, and region
- helps identify maintenance or customer-service interventions

### 2.6 Regional / Geographic Data
This table supports market-level analysis.

Recommended fields:
- Region_ID
- Region_Name
- City
- State / Province
- Market_Type (Urban / Rural / Semi-Urban)
- Sales_Area

Why this matters:
- allows performance comparison across regions
- helps identify underperforming areas or growth opportunities

### 2.7 Time Dimension
A time table improves trend analysis and reporting.

Recommended fields:
- Month_ID
- Month_Name
- Quarter
- Year
- Week_Number

Why this matters:
- supports monthly, quarterly, and annual analysis
- helps track revenue trends and seasonality

## 3. Ideal Dataset Scope
For a strong business analysis, the data should cover:
- at least 12 to 24 months of historical records
- both prepaid and postpaid customer groups
- multiple plans and regions
- usage, billing, and churn information for the same period

## 4. Key Business Questions This Dataset Will Answer
This dataset should enable answers to:
- Which customer segments generate the most revenue?
- Which plans are most profitable and most adopted?
- Are customers using more than they are paying for?
- Which regions have weak revenue performance?
- Which customer groups are most likely to churn?
- Where may revenue leakage be occurring?

## 5. Data Quality Requirements
Before analysis, the data should be checked for:
- unique and consistent Customer_ID values across tables
- standard date formats
- removal of duplicate records
- consistent plan and region naming
- valid positive values for revenue and usage
- proper handling of missing or null fields

## 6. Recommended Data Sources
If the data is being collected from internal systems, the most relevant sources are:
- CRM / customer database
- billing system
- subscription or plan management system
- usage and network reporting tools
- customer service / churn records
- regional sales or territory data

## 7. Minimum Starter Dataset
If a full enterprise dataset is not yet available, start with a sample dataset that includes:
- 5,000 to 20,000 customers
- 12 months of billing and usage records
- a mix of prepaid and postpaid users
- at least 5 to 10 plan types
- several geographic regions

This will be enough to build the first Excel pivots and initial Power BI prototype dashboards.

## 8. Expected Outcome
With the right dataset, the project can produce actionable insights into telecom revenue growth, customer profitability, churn risk, and possible revenue leakage, using Excel and Power BI as the main analytical tools.
