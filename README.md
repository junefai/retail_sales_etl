# Retail Store Sales – Data Cleaning Project

## Project Overview
This project focuses on cleaning and preparing a dirty retail store sales dataset using Python and Pandas.

The objective is to identify and address data quality issues, improve data consistency, handle missing values, and prepare the dataset for further analysis.

## Dataset
The dataset contains retail transaction records with information such as:

- Transaction ID
- Customer ID
- Category
- Item
- Price Per Unit
- Quantity
- Total Spent
- Payment Method
- Location
- Transaction Date
- Discount Applied

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Process

The following data quality checks and cleaning activities were performed:

1. **Missing Values:** Identified missing values and assessed how to handle them.
2. **Data Types:** Checked and corrected column data types, including converting transaction dates into datetime format.
3. **Duplicate Records:** Investigated duplicate records.
4. **Inconsistent Values:** Examined categorical columns for inconsistent formatting and labels.
5. **Outlier Detection:** Used descriptive statistics and the Interquartile Range (IQR) method to identify potential outliers.
6. **Data Validation:** Examined relationships between numerical columns to identify potential inconsistencies.

## Project Structure

```text
retail-store-sales-cleaning/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── README.md
└── requirements.txt
```

## Key Objectives

- Improve data quality and reliability.
- Identify inconsistencies and missing information.
- Apply appropriate data-cleaning techniques.
- Produce a dataset suitable for further exploratory data analysis.

## Future Work

- Perform exploratory data analysis (EDA).
- Identify retail sales trends and patterns.
- Develop visualizations to communicate insights.
