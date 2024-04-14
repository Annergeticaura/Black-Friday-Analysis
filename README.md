# Black Friday Sales Data Analysis

This repository contains Python code for analyzing Black Friday sales data. The dataset used for analysis is a fictional dataset that simulates sales transactions that occur on Black Friday.

## Dataset

The dataset used for analysis is stored in the `test.csv` file. It contains the following columns:

- User_ID: Unique identifier for each user
- Product_ID: Unique identifier for each product
- Gender: Gender of the user
- Age: Age group of the user
- Occupation: Occupation code of the user
- City_Category: Category of the city where the user resides (A, B, C)
- Stay_In_Current_City_Years: Number of years the user has stayed in the current city
- Marital_Status: Marital status of the user (0 - Single, 1 - Married)
- Product_Category_1: Category of the product
- Product_Category_2: Category of the product (if available)
- Product_Category_3: Category of the product (if available)


## Analysis

The Python script `black_friday_analysis.py` contains code for performing various analyses on the Black Friday sales data. It includes the following analyses:

1. Exploratory Data Analysis (EDA): Summary statistics, distribution of purchase amounts, etc.
2. Gender-based Analysis: Average purchase amount by gender.
3. Age-based Analysis: Average purchase amount by age group.
4. City-based Analysis: Purchase distribution across different city categories.
5. Product Category Analysis: Purchase distribution across different product categories.
6. Correlation Analysis: Correlation between different features.

## Requirements

To run the analysis script, you need to have Python installed on your system along with the following libraries:

- Pandas
- Matplotlib
- Seaborn

You can install the required libraries using the following command:

```bash
pip install pandas matplotlib seaborn
