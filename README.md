## Sales Analysis During Diwali
Description
This project analyzes the sales data of a retail store across various cities in India during the Diwali festival. The primary objective is to provide insights into:

Which cities have the highest sales
Which products are sold the most
Which age groups are purchasing the most
Using these insights, the store can target specific audiences and optimize their advertising campaigns to maximize sales.

# Installation
To run this project, you need to have the following software and dependencies installed:
Python 3.x - You can download and install Python from here.
Jupyter Notebook - For interactive data analysis. Install it using pip - pip install notebook
and pip install pandas numpy matplotlib seaborn

## Sales Analysis Project Summary

# Data Loading and Cleaning
Loading Data:

Imported necessary libraries: numpy, pandas, matplotlib, and seaborn.
Loaded the Diwali sales data from a CSV file using pd.read_csv.
Initial Data Inspection:

Checked the shape, head, tail, and basic info of the dataset to understand its structure.
# Data Cleaning:

Dropped unnecessary columns (Status and Unnamed).
Checked for and handled missing values:
Displayed rows with missing values.
Filled missing values in the 'Amount' column with the mean of the respective product category.
Converted the 'Amount' column to an integer type.
Renamed columns for clarity.
Exploratory Data Analysis (EDA)
Performed EDA on key performance indicator (KPI) columns to gain insights into sales patterns:

Gender Analysis:

Plotted the count of transactions by gender.
Analyzed total sales amount by gender.
Age Group Analysis:

Created age groups and plotted the count of transactions by age group and gender.
Analyzed total sales amount by age group.
State Analysis:

Analyzed the number of orders and total sales amount by state.
Plotted the top 10 states by number of orders and total sales amount.
Marital Status Analysis:

Plotted the count of transactions by marital status.
Analyzed total sales amount by marital status and gender.
Occupation Analysis:

Plotted the count of transactions by occupation.
Analyzed total sales amount by occupation.
Product Category Analysis:

Plotted the count of transactions by product category.
Analyzed total sales amount by product category.

# Key Insights
Married women aged 26-35 years from states like Uttar Pradesh, Maharashtra, and Karnataka, working in IT, healthcare, and aviation, are more likely to purchase products in the food, clothing, and electronics categories.

