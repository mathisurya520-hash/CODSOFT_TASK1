# CODSOFT Task 1: Data Cleaning and Preprocessing

## Project Overview
This project focuses on inspecting and preparing a retail sales dataset for further analysis using Python and Pandas. The dataset was examined for missing values, duplicate records, inconsistent entries, and incorrect data types.

## Objectives
- Import and inspect the retail sales dataset.
- Identify missing values and duplicate records.
- Check data consistency and data types.
- Convert the Date column into the correct datetime format.
- Validate transaction amounts.
- Export the processed dataset as a new CSV file.

## Dataset Description
The dataset contains 1,000 retail transactions and 9 columns.

The columns include:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Tools and Technologies
- Python
- Pandas
- Google Colab

## Data Cleaning Process
1. Imported the original dataset into Pandas.
2. Inspected the first five rows, dataset dimensions, column names, and data types.
3. Checked for missing values.
4. Checked for duplicate rows and duplicate transaction IDs.
5. Converted the Date column from object to datetime format.
6. Checked gender and product category values.
7. Validated age, quantity, price, and total amount values.
8. Saved the processed dataset as `retail_sales_cleaned.csv`.

## Results

| Validation | Result |
|---|---:|
| Total records | 1,000 |
| Total columns | 9 |
| Missing
