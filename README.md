# Banking Dashboard Power BI

## Project Overview
This project demonstrates a **Banking Dashboard** created using the latest Power BI tools to analyze client banking data and support risk analytics in banking and financial services. The dashboard is designed to help banks minimize losses while lending money by making data-driven decisions about loan approvals based on client profiles.

## Problem Statement
To develop a basic understanding of risk analytics in banking and financial services and how data is utilized to minimize lending risks.

## Dataset Information
The dataset consists of multiple interlinked tables with key banking and client information, including:
- Banking Relationship
- Client-Banking
- Gender
- Investment Advisor
- Period

## Data Cleaning & Preparation
Key data engineering steps include:
- Creating an **Engagement Timeframe** column representing the duration of client engagement.
- Calculating **Engagement Days** as the number of days a client has been with the bank.
- Categorizing clients into income bands (Low, Mid) based on estimated income.
- Defining a **Processing Fees** column corresponding to fee structure tiers.

## Important Calculated Functions
- **SUM**: Adds up numeric values in columns.
- **DISTINCTCOUNT**: Counts unique records.
- **SUMX**: Sums expressions evaluated per row in a table.
- **SWITCH**: Conditional expression evaluation.
- **DATEDIFF**: Calculates differences between dates.

## Key Performance Indicators (KPIs)
- **Total Clients**
- **Total Loan** (sum of bank loans, business lending, credit card balances)
- **Bank Loan**
- **Business Lending**
- **Total Deposit** (sum of bank deposit, savings, foreign currency, checking accounts)
- **Total Fees** (calculated from loans and processing fees)
- **Engagement Length**
- **Credit Card Balance**

## Visualizations
- Loan Analysis
- Deposit Analysis
- Summary Dashboard presenting aggregated KPIs

## Conclusion
Power BI dashboards are powerful tools in the banking sector for visualizing essential banking KPIs and turning data into actionable insights for risk management and decision-making in lending processes.

## Future Scope
- Enhanced customer segmentation for targeted banking strategies.
- Strategic insights based on bank type and client nationalities.
- Expansion to multi-bank or regional analysis with predictive capabilities.

## How to Use
1. Import the dataset into Power BI.
2. Recreate the calculated columns and measures using the given formulas.
3. Customize or extend visualizations based on specific analysis needs.
4. Utilize the dashboard for lending risk assessment and client management.

---

## Contact & Contributions
Please open an issue for questions or contribute via pull requests.

---
*This project enhances banking risk analytics through interactive Power BI dashboards.*
# banking-analysis-2
The goal of this project was to analyze banking customer and transaction data to gain insights into customer behavior, loan risk assessment, and financial performance
