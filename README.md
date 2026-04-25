# Financial Consumer Complaints Analysis Dashboard
## Project Overview
This project analyzes over 75,000 consumer complaints to uncover patterns in complaint trends, resolution performance, and customer satisfaction.

The goal was to transform raw complaint data into actionable insights that can help improve service delivery, reduce disputes, and enhance customer experience within a financial services environment.
## Business Problem
Cumulus Financial faced increasing consumer complaints but lacked clear visibility into:

- Key drivers of complaints
- Effectiveness of resolution strategies
- Factors contributing to customer dissatisfaction

This project addresses these gaps through a data-driven dashboard and analysis.
## Tools & Skills Used
- Microsoft Excel
  - Pivot Tables
  - XLOOKUP
  - Data Cleaning & Transformation
  - Dashboard Design
- Data Analysis
- Data Visualization
- KPI Development

## Dataset Description
The dataset includes:

- Complaint details (date, channel, product, issue)
- Resolution outcomes (timely response, dispute status)
- Customer interaction data

Supporting tables:
- Products table (product hierarchy)
- Issues table (issue classification)

## Data Cleaning & Preparation
Key steps included:
- Merged datasets using XLOOKUP to map product and issue details
- Converted state abbreviations to full names for clarity
- Created calculated fields:
    - Response Time (Days)
    - Data quality flag for inconsistent records
- Identified and handled missing values (notably in dispute status)
- Filtered Top 15 issues to improve visualization clarity

## Dashboard Features
The interactive Excel dashboard includes:

- KPIs
    * Total complaints
    * % timely responses
    * % disputed complaints
    * Average response time
- Visual Analysis
    * Complaint trends over time
    * Complaints by product
    * Top customer issues
    * Channel performance
    * Geographic distribution
    * Response type vs disputes
- Interactivity
    * Slicers for state, channel, and response timeliness

## Key Insights
- Complaint volume increased significantly over time, peaking in 2018
- Credit cards, bank accounts, and mortgages generate the highest complaints
- Top issues relate to:
    * Account management
    * Deposits & withdrawals
    * Payment difficulties
- Despite 98% timely responses, customer dissatisfaction persists
- Complaints resolved with explanations show higher dispute rates
- Complaints resolved with monetary relief show lower dispute rates
- Referral channels show disproportionately high dispute levels
- 49% of dispute data is missing, indicating data quality challenges

## Recommendations

Based on the analysis:
- Improve resolution quality by reducing reliance on explanation-only responses
- Prioritize high-risk issues related to transactions and account management
- Implement product-specific support teams
- Strengthen handling of escalated (referral) complaints
- Improve data collection and tracking of dispute outcomes
- Enhance digital complaint handling and self-service tools

## Business Impact
If implemented, these strategies can:
- Reduce dispute rates
- Improve customer satisfaction
- Enhance operational efficiency
- Support better resource allocation

## Project Files

## About Me
I’m an aspiring data analyst with a strong interest in using data to solve real-world business problems, particularly in finance and healthcare.
