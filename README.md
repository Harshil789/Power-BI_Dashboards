# Phone Sales Analysis Dashboard

## Project Overview

This project is a Power BI dashboard developed to analyze phone sales data and provide an interactive view of sales performance, customer behavior, product performance, payment methods, and geographical distribution.

The dashboard converts transaction-level sales data into a set of interactive visualizations and key performance indicators. Users can filter the report by mobile model, customer, brand, city, and month to analyze the data from different perspectives.

The project was developed using Microsoft Power BI Desktop, with the data imported into Power BI and analyzed using calculated measures and interactive report visuals.

---

## Objectives

The main objectives of this project are:

- Analyze overall phone sales performance.
- Monitor total sales and total quantity sold.
- Track the number of sales transactions.
- Analyze sales performance by mobile model and brand.
- Understand sales trends across months and days of the week.
- Analyze customer ratings.
- Understand the distribution of transactions across payment methods.
- Analyze sales across different cities.
- Provide an interactive dashboard for exploring sales data.

---

## Dataset

The dashboard is built using a transaction-level phone sales dataset.

Each row represents a sales transaction and contains information related to the transaction, customer, product, location, and payment method.

### Dataset Fields

| Field | Description |
|---|---|
| Transaction ID | Unique identifier for each sales transaction |
| Date | Date on which the transaction took place |
| Day Name | Day of the week associated with the transaction |
| Brand | Phone brand |
| Units Sold | Number of units sold in the transaction |
| Price Per Unit | Selling price of the phone per unit |
| Customer Name | Name of the customer |
| Customer Age | Age of the customer |
| City | Customer/sales location |
| Payment Method | Method used to complete the transaction |
| Customer Ratings | Rating provided by the customer |
| Mobile Model | Phone model purchased |

---

## Data Preparation

The dataset was imported into Power BI Desktop using Import storage mode.

The data was reviewed and prepared before creating the dashboard. The preparation process included checking the available fields, assigning appropriate data types, and making the data suitable for analysis and visualization.

The report uses the `Sales_Data` table as the primary data source.

The data contains transaction, product, customer, geographical, payment, and rating information, allowing the dashboard to provide multiple views of the sales performance.

---

## Data Model

The current Power BI report uses a transaction-level `Sales_Data` table.

The table contains the fields required for the analysis, including:

- Transaction information
- Date information
- Product information
- Customer information
- Location information
- Payment information
- Customer ratings

Calculated measures were created within Power BI to derive the main KPIs displayed on the dashboard.

---

## DAX Measures

Several measures were created to calculate the key metrics used throughout the report.

### Total Sales

Calculates the total sales value based on the available sales data.

### Total Quantity

Calculates the total number of units sold.

### Total Transactions

Calculates the number of transactions recorded in the dataset.

### Average Sales / Price Per Unit

Used to analyze the average selling value of the products.

These measures make the dashboard dynamic so that the displayed results change according to the filters selected by the user.

---

## Dashboard Structure

The dashboard is designed as an interactive sales analysis report.

The main report contains KPI cards, slicers, a geographical map, trend analysis, product analysis, payment method analysis, and customer rating analysis.

### Key Performance Indicators

The top section of the dashboard provides an overview of the selected data through four KPI cards:

- Total Sales
- Total Quantity
- Total Transactions
- Average Price Per Unit

These KPIs provide an immediate overview of the selected sales data.

---

## Interactive Filters

The dashboard provides multiple filters that allow users to explore the dataset interactively.

### Mobile Model

Allows users to select a specific phone model and analyze its performance.

### Customer Name

Allows the analysis to be filtered for an individual customer.

### Brand

Allows users to compare or focus on a specific phone brand.

### City

Allows the sales analysis to be filtered geographically.

### Month

The month selector allows users to analyze sales performance for individual months throughout the year.

These filters interact with the other visuals on the report, allowing users to perform focused analysis without modifying the underlying dataset.

---

## Sales by Location

A map visual is used to display the geographical distribution of sales across cities.

The map provides a visual representation of the locations included in the dataset and helps identify the geographical spread of the sales transactions.

This can be useful for understanding where sales activity is concentrated.

---

## Quantity Sold by Month

The `Total_Quantity by Month` line chart shows how the number of units sold changes across the selected period.

This visualization can be used to identify:

- High-volume months
- Low-volume months
- Changes in demand
- Overall sales volume patterns

The interactive filters allow the monthly trend to be analyzed for different products, brands, customers, and locations.

---

## Total Sales by Brand

The `Total_Sales by Brand` visual provides a comparison of sales performance across phone brands.

This allows users to identify which brands contribute most to the overall sales value.

The visual can also be combined with the Mobile Model and City filters to investigate brand performance in greater detail.

---

## Transactions by Payment Method

The payment method visualization shows the distribution of transactions across different payment methods.

The dataset includes payment methods such as:

- UPI
- Credit Card
- Debit Card
- Cash

This analysis provides an overview of customer payment preferences and the proportion of transactions associated with each payment method.

---

## Customer Ratings Analysis

The `Sum of Customer Ratings by Customer Ratings` visual shows the distribution of customer ratings in the dataset.

The dashboard can be used to understand how transactions are distributed across different rating levels.

This provides an additional customer satisfaction perspective alongside the sales analysis.

---

## Sales by Day of the Week

The `Total_Sales by Day Name` visualization compares sales performance across different days of the week.

This allows the analysis of sales patterns across:

- Monday
- Tuesday
- Wednesday
- Thursday
- Friday
- Saturday
- Sunday

The visualization can help identify which days contribute the most and least to total sales.

---

## Mobile Model Performance

A table visual is included to display sales performance by mobile model.

The table provides a direct comparison between the selected mobile model and its corresponding total sales value.

This allows users to quickly evaluate product-level performance.

---

## Dashboard Interaction

The report is designed so that the different visuals work together.

For example, selecting a particular mobile model can update the KPI cards, sales trends, geographical analysis, payment distribution, and other report visuals.

This interactive approach allows the dashboard to be used for both high-level performance monitoring and detailed analysis.

---

## Business Questions Answered

The dashboard can be used to answer questions such as:

1. What is the total sales value?
2. How many units have been sold?
3. How many transactions have been recorded?
4. What is the average price per unit?
5. Which phone brands generate the highest sales?
6. Which mobile models contribute most to sales?
7. How does sales quantity change from month to month?
8. Which days of the week generate higher sales?
9. How are transactions distributed across payment methods?
10. Which cities are represented in the sales data?
11. How are customers distributed across different rating levels?
12. How does sales performance change when filtering by mobile model, brand, city, customer, or month?

---

## Dashboard Development Process

The project followed a typical Power BI development workflow:

```text
Transaction Data
      |
      v
Data Import
      |
      v
Data Preparation
      |
      v
Data Validation
      |
      v
Power BI Data Model
      |
      v
DAX Measures
      |
      v
Report Visualizations
      |
      v
Interactive Filters
      |
      v
Final Dashboard
