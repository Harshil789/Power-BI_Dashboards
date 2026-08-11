# 📱 Phone Sales Analysis Dashboard – Power BI

## 📊 Project Overview

This project is an interactive **Phone Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this dashboard is to transform raw phone sales data into meaningful business insights that can help understand sales performance, customer purchasing behavior, product performance, and overall business trends.

The dashboard follows a complete Business Intelligence workflow:

**Raw Data → Data Preparation → Data Modeling → DAX Calculations → Data Visualization → Business Insights**

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall phone sales performance.
- Track total sales and key performance indicators (KPIs).
- Identify top-performing phone models and brands.
- Analyze sales trends over time.
- Understand customer purchasing patterns.
- Compare sales performance across different categories.
- Provide an interactive interface for exploring the data.
- Convert raw transactional data into actionable business insights.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and business calculations |
| **Data Modeling** | Creating relationships between tables |
| **Git & GitHub** | Project version control and documentation |

---

# 🔄 Data Preparation Process

The dashboard was developed through several stages.

## 1. Data Collection

The first step was to load the phone sales dataset into Power BI.

The dataset contains sales-related information that can be analyzed across different business dimensions such as:

- Phone/Model
- Brand
- Sales
- Quantity
- Date
- Customer-related attributes
- Geographic or categorical information where available

The data was imported into Power BI Desktop and inspected before beginning the transformation process.

---

## 2. Data Cleaning & Transformation

The raw dataset was prepared using **Power Query**.

The transformation process included typical data preparation activities such as:

- Removing unnecessary columns.
- Removing duplicate records where required.
- Handling missing or blank values.
- Correcting column data types.
- Standardizing column names.
- Formatting date fields.
- Checking numerical fields for consistency.
- Creating useful columns required for analysis.
- Validating the transformed data before loading it into the model.

Power Query was used to ensure that the data entering the Power BI model was clean, consistent, and suitable for analysis.

---

## 3. Data Modeling

After cleaning the data, the next step was to create the Power BI data model.

Relationships between relevant tables/fields were established so that filters and calculations could correctly flow through the model.

The model was designed with analytical reporting in mind, allowing the dashboard to analyze sales from different perspectives.

A well-structured data model is important because the visuals, filters, and DAX measures depend on the relationships between the underlying tables.

---

# 🧮 DAX & Business Calculations

DAX (Data Analysis Expressions) was used to create measures required for the dashboard.

The calculations were designed to provide dynamic results based on the filters and selections made by the user.

Examples of analytical calculations used in a sales dashboard include:

- Total Sales
- Total Quantity Sold
- Average Sales
- Number of Transactions
- Sales by Brand
- Sales by Model
- Sales by Date
- Top-performing products
- Percentage contribution
- Period-over-period analysis

DAX measures allow these calculations to respond dynamically when users interact with slicers and other report filters.

---

# 📈 Dashboard Development

After preparing the data model and calculations, the report pages were designed in Power BI.

The dashboard uses interactive Power BI visuals to present the most important information in an easy-to-understand format.

The report can include visual components such as:

### KPI Cards

Used to provide a quick overview of important metrics such as:

- Total Sales
- Total Quantity
- Number of Transactions
- Average Sales

### Trend Analysis

Charts can be used to understand how sales change over time.

This helps identify:

- Growth or decline in sales
- Seasonal patterns
- High-performing periods
- Changes in customer demand

### Product Analysis

Product-level analysis helps identify which phone models or brands contribute most to overall sales.

This can be used to determine:

- Best-selling products
- Highest-revenue products
- Low-performing products
- Brand performance

### Interactive Filters

Slicers and filters allow users to dynamically explore the report.

Users can filter the dashboard by relevant dimensions such as:

- Date
- Brand
- Phone model
- Category
- Location
- Other available business dimensions

When a filter is selected, the relevant KPIs and visualizations update automatically.

---

# 🔍 Business Insights

The dashboard is designed to answer important business questions such as:

### Sales Performance

- How much revenue is being generated?
- How many units are being sold?
- How is sales performance changing over time?

### Product Performance

- Which phone models perform best?
- Which brands generate the most sales?
- Which products may require further attention?

### Customer & Market Analysis

- Which customer segments contribute most to sales?
- Which markets or locations perform best?
- Are there noticeable differences in purchasing behavior?

### Trend Analysis

- Which periods have the highest sales?
- Are there seasonal trends?
- Are sales increasing or decreasing over time?

---

# 📊 Dashboard Workflow

The complete workflow followed for this project can be summarized as:

```text
Raw Phone Sales Data
        ↓
Data Import
        ↓
Power Query Transformation
        ↓
Data Cleaning & Validation
        ↓
Data Modeling
        ↓
Relationships
        ↓
DAX Measures
        ↓
Report & Visual Design
        ↓
Interactive Dashboard
        ↓
Business Insights
