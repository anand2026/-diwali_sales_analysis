# 🪔 Diwali Sales Analysis

## Project Description

This project analyzes Diwali sales data to uncover customer purchasing patterns and improve business strategies. Using Python and data analysis libraries, we explore sales trends across demographics, regions, and product categories.

## Dataset

- **Source:** Diwali Sales Dataset (CSV)
- **Records:** 11,251 transactions
- **Features:** 15 columns including User ID, Gender, Age Group, State, Occupation, Product Category, Orders, Amount, and more.

## Tech Stack

- **Python 3**
- **NumPy** – Numerical computing
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

## Data Cleaning & Preprocessing

1. Dropped unrelated/blank columns (`Status`, `unnamed1`)
2. Handled null values by dropping incomplete records
3. Converted `Amount` column to integer data type for accurate calculations
4. Renamed columns for better readability

## Exploratory Data Analysis

The analysis covers the following dimensions:

### 👫 Gender Analysis
- Visualized buyer count by gender
- Compared total purchase amount across genders
- **Finding:** Most buyers are **females**, and their purchasing power is greater than males

### 🎂 Age Group Analysis
- Analyzed buyer distribution across age groups with gender breakdown
- Compared total spending by age group
- **Finding:** Most buyers belong to the **26-35 years** age group, predominantly female

### 🗺️ State-wise Analysis
- Identified top 10 states by number of orders
- Identified top 10 states by total sales amount
- **Finding:** **Uttar Pradesh, Maharashtra, and Karnataka** lead in both orders and total sales

### 💍 Marital Status Analysis
- Explored buyer count by marital status
- Analyzed spending patterns by marital status and gender
- **Finding:** **Married women** are the highest spenders with strong purchasing power

### 💼 Occupation Analysis
- Visualized buyer distribution across occupations
- Compared total spending by occupation
- **Finding:** Buyers working in **IT, Healthcare, and Aviation** sectors dominate purchases

### 🛍️ Product Category Analysis
- Identified most sold product categories
- Analyzed top 10 most sold individual products by Product ID
- **Finding:** **Food, Clothing, and Electronics** are the most popular product categories
