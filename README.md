# 🪔 Diwali Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

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

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/anand2026/-diwali_sales_analysis.git
   cd -diwali_sales_analysis
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Diwali_Sales_Analysis.ipynb
   ```

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

## Conclusion

> **Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are more likely to buy products from Food, Clothing, and Electronics categories.**

This insight can help businesses:
- **Target marketing campaigns** towards married women in the 26-35 age group
- **Focus inventory** on Food, Clothing, and Electronics for Diwali season
- **Prioritize** states like UP, Maharashtra, and Karnataka for regional promotions
- **Tailor advertisements** for professionals in IT, Healthcare, and Aviation

## Project Structure

```
diwali_sales_analysis/
├── Diwali Sales Data.csv          # Raw sales dataset
├── Diwali_Sales_Analysis.ipynb    # Jupyter notebook with full analysis
├── requirements.txt               # Python dependencies
├── .gitignore                     # Git ignore rules
└── README.md                      # Project documentation
```

## License

This project is open source and available for educational purposes.

## Acknowledgements

- Dataset sourced from Kaggle
- Inspired by real-world Diwali festive season sales data
- Built as a data analysis practice project using Python

---

⭐ If you found this project helpful, give it a star!
