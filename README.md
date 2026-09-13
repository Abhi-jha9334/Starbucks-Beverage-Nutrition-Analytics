# Starbucks Beverage & Nutrition Analytics

## Project Overview

An end-to-end data analytics and business intelligence project focused on analyzing Starbucks beverage products and their nutritional characteristics.

The project follows a structured data pipeline covering data quality assessment, Python-based data cleaning, SQL analysis, data transformation, analytical modeling, and interactive Power BI dashboard development.

The objective is to transform raw beverage data into meaningful business and nutritional insights around product portfolio distribution, calories, sugar, and caffeine.

---

## Business Objective

The primary objective is to analyze Starbucks beverage products and understand how nutritional characteristics vary across different beverage categories.

The analysis focuses on:

- Product portfolio distribution
- Category-level nutritional differences
- Average calorie, sugar, and caffeine levels
- Beverage category comparison
- Nutritional patterns across the product portfolio

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

The dataset contains *242 beverage records* and *33 distinct beverage products* after data preparation.

---

## Data Cleaning & Preparation

Python and Pandas were used for data cleaning and preparation.

Key activities included:

- Data quality assessment
- Missing-value checking
- Identification of inconsistent values
- Correction of data inconsistencies
- Data type standardization
- Numerical field validation
- Preparation of the cleaned dataset for downstream analysis

The cleaned dataset was validated before being used for SQL analysis and Power BI development.

---

## Data Pipeline & Transformation

The project follows a structured data transformation workflow from raw data to the final analytics layer.

```text
Raw Starbucks Dataset
        ↓
Data Quality Assessment
        ↓
Python & Pandas Transformation
        ↓
Cleaned Dataset
        ↓
SQL Analysis using DuckDB
        ↓
Power Query Transformation
        ↓
Data Modeling & DAX
        ↓
Power BI Analytics Layer
        ↓
Business Insights
