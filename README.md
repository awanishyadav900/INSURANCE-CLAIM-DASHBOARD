🛡️ Insurance Claims Analytics Dashboard

A Power BI data analytics project focused on analyzing insurance claim data to uncover trends, detect risk patterns, and support data-driven decision-making in the insurance domain.

This dashboard transforms raw claims data into interactive visual insights for business stakeholders.

📌 Project Overview

Insurance companies handle thousands of claims, and understanding patterns behind:

Claim frequency

Claim severity

Fraud indicators

Policyholder risk

Settlement timelines

…is critical for profitability and operational efficiency.

This dashboard provides a centralized analytics solution to monitor key insurance claim metrics and performance indicators.

🎯 Objectives

Analyze claim trends over time

Identify high-risk customer segments

Monitor claim settlement performance

Detect anomalies and potential fraud patterns

Support business decisions with visual insights

🧰 Tools & Technologies
Tool	Purpose
Power BI	Data modeling & interactive dashboard
Power Query	Data cleaning and transformation
DAX	Measures, KPIs, and calculations
Excel / CSV (Data Source)	Raw insurance claims dataset
📊 Dashboard Features
1️⃣ Claims Overview

Total number of claims

Total claim amount

Average claim cost

Claim approval vs rejection rate

2️⃣ Time-Based Analysis

Claims trend by month/year

Seasonal patterns

Claim volume growth

3️⃣ Customer & Policy Insights

Claims by age group

Claims by policy type

High-risk demographics

4️⃣ Financial Analysis

Total payout amount

Average settlement time

Cost distribution by claim type

5️⃣ Risk & Fraud Indicators

Unusual high-value claims

Repeat claimants

Claim frequency by customer

📈 Key KPIs Used

Total Claims

Total Claim Amount

Average Claim Amount

Claim Approval Rate

Average Settlement Time

High-Risk Claim Percentage

🧮 Data Modeling

The dashboard uses a structured data model including:

Claims Table – Claim ID, date, type, amount, status

Customers Table – Demographics, policyholder details

Policy Table – Policy type, coverage, premium

Time Dimension – Date hierarchy for trend analysis

Relationships are built to enable accurate aggregation and filtering.

⚙️ Data Cleaning & Transformation

Performed using Power Query:

Removed duplicates

Handled missing values

Standardized date formats

Created calculated columns

Categorized claim amounts into bands

🧠 DAX Measures Examples
Total Claims = COUNT(Claims[Claim ID])

Total Claim Amount = SUM(Claims[Claim Amount])

Average Claim Amount = DIVIDE([Total Claim Amount], [Total Claims])

Claim Approval Rate = 
DIVIDE(
    CALCULATE(COUNT(Claims[Claim ID]), Claims[Status] = "Approved"),
    [Total Claims]
)

🖥️ How to Use

Download the .pbix file from this repository

Open using Microsoft Power BI Desktop

Explore report pages using slicers and filters

Interact with visuals for drill-down analysis

🚀 Business Value

This dashboard helps:

✔ Insurance managers monitor performance
✔ Analysts detect risk trends
✔ Operations teams improve settlement efficiency
✔ Executives make data-driven decisions

🔮 Future Improvements

Add fraud detection scoring model

Real-time data integration

Predictive claim cost modeling

Customer churn risk analysis

# screenshot

![image_alt](https://github.com/awanishyadav900/INSURANCE-CLAIM-DASHBOARD/blob/main/Screenshot%202026-02-03%20221100.png)
