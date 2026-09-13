# Starbucks Beverage & Nutrition Analytics

## Project Overview

An end-to-end data analytics project focused on analyzing Starbucks beverage products and their nutritional characteristics.

The project follows a complete analytics workflow, from data cleaning and exploratory analysis to SQL-based analysis and interactive Power BI dashboard development.

The objective is to understand product portfolio distribution and compare key nutritional metrics such as calories, sugar, and caffeine across beverage categories.

---

## Business Objective

The primary objective of this project is to transform raw Starbucks beverage data into meaningful analytical insights that can support product portfolio analysis and nutritional comparison.

The analysis focuses on understanding:

- Product distribution across beverage categories
- Category-level nutritional differences
- Average calorie, sugar, and caffeine levels
- Product portfolio composition
- Patterns that can help compare beverage categories from a nutritional perspective

---

## Business Logic & Analytical Questions

The analysis was designed around the following business questions:

1. Which beverage categories contain the highest number of products?
2. How are Starbucks products distributed across beverage categories?
3. What is the average calorie level for each beverage category?
4. Which beverage categories have higher average sugar content?
5. How does average caffeine content vary across beverage categories?
6. Which categories show relatively higher nutritional values?
7. How can category-level nutritional metrics support product comparison and portfolio analysis?

These business questions were translated into SQL queries, analytical measures, KPIs, and Power BI visualizations.

---

## Dataset

The dataset contains Starbucks beverage products along with their nutritional and categorical attributes.

Key attributes include:

- Beverage
- Beverage Category
- Calories
- Caffeine (mg)
- Sugars (g)
- Total Fat (g)
- Other nutritional attributes

The cleaned dataset contains *242 beverage records* and *33 distinct beverage products*.

---

## Data Cleaning & Preparation

Python and Pandas were used for data cleaning and preparation.

Key activities included:

- Data quality assessment
- Checking missing values
- Identifying inconsistent values
- Correcting data inconsistencies
- Converting numerical columns into appropriate data types
- Validating cleaned nutritional metrics
- Preparing the dataset for SQL analysis and Power BI

---

## SQL Analysis

SQL analysis was performed using DuckDB.

The SQL analysis focused on:

- Product and category counts
- Category-level aggregation
- Average nutritional metrics
- Beverage category comparisons
- Nutritional metric exploration
- Supporting business questions with structured queries

SQL was used to convert raw data into analytical results that could be further visualized in Power BI.

---

## Power BI Dashboard

The cleaned and analyzed data was used to develop an interactive Power BI dashboard with a Starbucks-inspired professional design.

### Page 1 — Executive Overview

The Executive Overview provides a high-level summary of the beverage portfolio.

*KPIs:*

- Total Products
- Average Calories
- Average Caffeine
- Average Sugar

*Visualizations:*

- Products by Beverage Category
- Average Calories by Beverage Category
- Beverage Category slicer

*Interactive Features:*

- Category filtering
- Reset Filters button
- Report-page tooltip
- Interactive visual filtering

---

### Page 2 — Nutritional Insights

The Nutritional Insights page provides detailed category-level nutritional comparisons.

*Visualizations:*

- Average Calories by Beverage Category
- Average Sugar by Beverage Category
- Average Caffeine by Beverage Category
- Product Distribution by Beverage Category

The page is designed to make nutritional differences between beverage categories easier to compare and interpret.

---

## Key Metrics

| Metric | Value |
|---|---:|
| Total Products | 33 |
| Average Calories | 194 |
| Average Caffeine | 90 mg |
| Average Sugar | 33 g |
| Total Records | 242 |

Values are rounded for dashboard presentation.

---

## Analytical Insights

The analysis enables comparison of beverage categories based on:

- Product portfolio size
- Average calorie content
- Average sugar content
- Average caffeine content
- Overall product distribution

These comparisons provide a structured view of how nutritional characteristics differ across beverage categories and help identify categories with relatively higher or lower average nutritional values.

---

## Tools & Technologies

### Data Analysis
- Python
- Pandas

### Database & SQL
- SQL
- DuckDB

### Business Intelligence
- Power BI
- Power Query
- DAX

### Data Preparation
- Microsoft Excel

---

## Project Workflow

```text
Raw Dataset
     ↓
Data Quality Assessment
     ↓
Python & Pandas Data Cleaning
     ↓
SQL Analysis using DuckDB
     ↓
Power Query Transformation
     ↓
Data Modeling & DAX
     ↓
Power BI Dashboard
     ↓
Business & Nutritional Insights
