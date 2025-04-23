# Supermarket Product Recommendation System

This project performs market basket analysis using the FP-Growth algorithm to recommend products in a supermarket scenario. It analyzes transaction data to find frequent patterns and association rules, helping identify which products are likely to be bought together.

## Features

- Data cleaning and preprocessing
- Transaction encoding for market basket analysis
- Frequent itemset mining using FP-Growth
- Association rule generation with support, confidence, and lift
- Basic recommendation function based on customer basket

## Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- mlxtend (for FP-Growth and association rules)
- Jupyter Notebook

## Setup Instructions

1. Clone the repository or download the notebook file.
2. Install the required libraries using pip:

## Install the dependencies:
````bash
pip install pandas numpy matplotlib seaborn mlxtend 
````

## How It Works
- __Data Cleaning:__ Removes missing values, duplicates, and irrelevant stock codes.
- __Basket Creation:__ Groups purchases by Invoice and CustomerID.
- __Frequent Pattern Mining:__ Uses FP-Growth to find common itemsets.
- __Association Rules:__ Filters rules by confidence and lift.
- __Recommendation:__ Provides the next best product based on the current cart.

## Sample Output
- Association rules with metrics (support, confidence, lift)
- Recommended products based on user's cart contents
