# Customer Churn and Retention Analysis

## Project Overview

This project analyzes customer churn and retention patterns using Microsoft Excel. The goal is to identify customer groups with higher churn rates and understand the factors associated with customer attrition.

The analysis uses customer demographic, service, contract, payment, tenure, and billing information to create an interactive dashboard that supports data-driven retention analysis.

## Business Objective

Customer churn can reduce revenue and increase the cost of acquiring new customers. This project aims to:

- Measure the overall customer churn rate.
- Identify customer segments with higher churn rates.
- Analyze churn based on contract type.
- Compare churn across tenure groups.
- Examine the relationship between payment methods and churn.
- Analyze churn by internet service type.
- Compare churn among senior and non-senior customers.
- Examine the relationship between technical support and churn.
- Present findings through an interactive Excel dashboard.

## Tools and Technologies

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel formulas
- Interactive slicers
- Data cleaning and transformation
- Dashboard design

## Dataset

The project uses the IBM Telco Customer Churn dataset. The dataset contains customer-level information related to:

- Customer demographics
- Tenure
- Contract type
- Internet service
- Payment method
- Monthly charges
- Total charges
- Technical support
- Churn status

The data was cleaned and transformed before analysis.

## Data Cleaning

The following data preparation steps were performed:

- Imported the raw dataset into Excel.
- Used Power Query for data cleaning and transformation.
- Removed duplicate records.
- Checked and prepared columns for analysis.
- Created a numerical churn flag.
- Created customer tenure groups.
- Created monthly charge groups.
- Created a readable customer status field for senior and non-senior customers.

## Key Performance Indicators

The dashboard includes the following KPIs:

- Total Customers
- Churn Rate
- Average Tenure
- Average Monthly Charges

## Key Findings

The analysis identified the following patterns:

1. Month-to-month customers have a higher churn rate than customers with one-year or two-year contracts.
2. Customers within their first six months show a high churn rate.
3. Electronic check users have a comparatively high churn rate.
4. Customers without technical support have a higher churn rate than customers with technical support.
5. Fiber optic customers show a comparatively high churn rate.
6. Senior customers have a higher churn rate than non-senior customers in this dataset.

These findings can help businesses focus on early-stage customer engagement, contract conversion, payment experience, technical support, and service quality.

## Dashboard Features

The interactive dashboard includes:

- KPI cards
- Churn analysis by contract type
- Churn analysis by tenure group
- Churn analysis by payment method
- Churn analysis by internet service
- Churn analysis by contract type and payment method
- Churn analysis by senior citizen status
- Churn analysis by technical support
- Interactive slicers for filtering the analysis

## Project Files

- `Customer_Churn_and_Retention_Analysis.xlsx` — Complete Excel analysis workbook
- `customer_churn_dashboard_preview.png` — Dashboard preview image

## Conclusion

This project demonstrates the use of Excel for data cleaning, exploratory analysis, PivotTable-based reporting, and interactive dashboard creation. It highlights how customer data can be transformed into meaningful business insights related to churn and retention.

## Author

Created as part of my data analytics portfolio to demonstrate practical skills in Excel, data cleaning, business analysis, and dashboard development.
