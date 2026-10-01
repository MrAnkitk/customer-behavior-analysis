# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchase records across multiple product categories.

The objective is to clean and analyze customer data, identify purchasing patterns, understand customer segments, evaluate product and discount behavior, and present business insights through an interactive Power BI dashboard.

The project follows an end-to-end data analytics workflow:

Python → Data Cleaning → MySQL → SQL Analysis → Power BI → Business Report → Presentation

---

## Business Objectives

The analysis focuses on answering key business questions such as:

- How does revenue vary by gender and age group?
- Which products receive the highest customer ratings?
- Which products have the highest discount dependency?
- What are the most purchased products within each category?
- How do subscribers compare with non-subscribers?
- What percentage of customers belong to New, Returning, and Loyal segments?
- Are repeat buyers more likely to subscribe?
- How does shipping type relate to average purchase amount?
- Which customer groups contribute the most revenue?

---

## Dataset

The dataset contains customer demographics, purchase information, and shopping behavior.

### Dataset Summary

- Records: 3,900
- Columns: 18 original columns
- Missing Values: 37 missing values in Review Rating

### Key Features

**Customer Information**
- Customer ID
- Age
- Gender
- Location
- Subscription Status

**Purchase Information**
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

**Shopping Behavior**
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

---

## Tools & Technologies

### Python
- Pandas
- NumPy
- Jupyter Notebook

Used for:
- Data loading
- Data exploration
- Data cleaning
- Missing-value treatment
- Feature engineering
- Exploratory Data Analysis

### MySQL
Used for:
- Storing cleaned data
- SQL-based business analysis
- Aggregation and filtering
- Customer segmentation
- Ranking products
- Business KPI analysis

### Power BI
Used for:
- Interactive dashboard development
- KPI visualization
- Category analysis
- Customer analysis
- Revenue analysis

### Other Deliverables
- Business Analysis Report
- PowerPoint Presentation
