# Power BI Dashboard Report

## Prepared by: [Sasanika Ruwanthi]
## Date: [22/07/2024]

---

![image](https://github.com/user-attachments/assets/2f969798-6e23-466b-8dc1-890d0d37217b)
![image](https://github.com/user-attachments/assets/2b663846-9b8d-4104-a06d-315bd78f8eea)
![image](https://github.com/user-attachments/assets/b58078ac-5eb5-486d-a6c6-8933c8499c59)


## Introduction

Steven, Sales Manager, identified a need to improve internet sales reports by transitioning from static reports to dynamic visual dashboards. This initiative aims to enhance the ability to track sales performance over time, analyze sales by products and customers, and compare actual sales against budgeted figures. The solution employs Power BI for creating the dashboard and SQL for data manipulation and retrieval, using the AdventureWorksDW.bak database.

---

## Business Demand Overview

**Reporter:** Steven – Sales Manager  
**Value of Change:** Visual dashboards and improved sales reporting  
**Necessary Systems:** Power BI, CRM System  
**Other Relevant Info:** Budgets provided in Excel for 2021  

---

## User Stories

| No | As a (role)           | I want (request/demand)                 | So that I (user value)                                 | Acceptance Criteria                                 |
|----|-----------------------|------------------------------------------|--------------------------------------------------------|----------------------------------------------------|
| 1  | Sales Manager         | A dashboard overview of internet sales  | Can follow which customers and products sell best      | A Power BI dashboard updated daily                 |
| 2  | Sales Representative  | Detailed overview of Internet Sales per Customer | Can follow up with top customers and identify new opportunities | A Power BI dashboard with customer filtering       |
| 3  | Sales Representative  | Detailed overview of Internet Sales per Product | Can track top-selling products                        | A Power BI dashboard with product filtering        |
| 4  | Sales Manager         | Dashboard overview of internet sales    | Follow sales over time against budget                 | A Power BI dashboard with graphs and KPIs comparing to budget |

---

## Dashboard Development

### Database Selection and Preparation

**Database Used:** AdventureWorksDW.bak  

**Cleaning Process:**
- Removed unnecessary columns to streamline data processing and enhance performance.
- Ensured data consistency and integrity across the relevant tables.

**Key Database Tables:**
- **Calendar:** Contains date-related information to support time-based filtering.
- **Customers:** Stores customer information, crucial for customer-specific sales analysis.
- **Products:** Contains details about products, necessary for product-specific analysis.
- **Budget:** Holds budget data for comparison with actual sales.
- **InternetSales:** Records internet sales transactions.

### Dashboard Components and Features

**Filters:**
- Year
- Month
- Customer City
- Sub-category
- Category
- Product Name

**Visualizations:**
- **Sales vs. Budget Card:** Provides a quick comparison of actual sales against the budget.
- **Pie Chart on Sales by Product Category and Product:** Shows the distribution of sales across different product categories.
- **Line Plot on Sales and Budget by Month:** Tracks monthly sales and compares them with the budget.
- **Bar Chart on Sales by Top 10 Customers:** Highlights the top 10 customers by sales volume.
- **Map on Sales by Customer City:** Geographical representation of sales distribution across various cities.

---

## Technical Implementation

### Power BI Skills Demonstrated
- **Data Cleaning and Preparation:** Imported the cleaned data from AdventureWorksDW.bak, ensuring it was ready for analysis.
- **Data Modeling:** Established relationships between tables to support comprehensive analysis.
- **DAX Calculations:** Created measures and calculated columns to derive insights, such as sales performance against budget.
- **Visualization Techniques:** Used various visualization tools within Power BI to create an interactive and insightful dashboard.

### SQL Skills Demonstrated
- **Data Extraction:** Wrote SQL queries to extract relevant data from the AdventureWorksDW database.
- **Data Cleaning:** Performed data cleaning operations within SQL to remove unnecessary columns and ensure data accuracy.
- **Data Transformation:** Transformed data to the required format for analysis in Power BI.
- **Performance Optimization:** Optimized SQL queries to ensure efficient data retrieval and processing.

---

## Conclusion

The developed Power BI dashboard effectively meets the business demand for enhanced sales reporting and analysis. By leveraging advanced Power BI features and SQL capabilities, the solution provides dynamic, interactive, and insightful visualizations that empower the sales team to make informed decisions and track performance against budget.

For any further assistance or modifications, please feel free to reach out.

---

## Attachments

- Power BI Dashboard File
- SQL Query Scripts
- Data Cleaning Documentation

---

## Prepared by:
[Sasanika Ruwanthi]  
[sasanikaruwanthi@gmail.com]
