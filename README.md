# RUSH Sportswear Sales Analysis

## Project Overview

This project analyzes sales data for RUSH Sportswear to identify sales trends, answer key business questions, and provide business-relevant insights for company leadership.

The analysis was completed using Python and exploratory data analysis (EDA) techniques. Three tables were used in the analysis: product, retailer, and sales data.

## Business Questions

The analysis answers the following questions:

1. What product category had the highest sales in dollars in 2021, and how much did it sell?
2. What state had the highest sales in dollars of women's products in 2021, and how much was it?
3. What state had the highest sales in dollars of men's products in 2021, and how much was it?
4. What retailer purchased the most units in 2021? In 2020?

## Key Findings

- Men's Street Footwear generated the highest product sales in 2021 at approximately $74.6 million.
- Maine had the highest sales of women's products in 2021 at approximately $2.18 million.
- New Hampshire had the highest sales of men's products in 2021 at approximately $54.2 million.
- Foot Locker had the most units sold in 2021, with approximately 1.10 million units.
- Amazon had the most units sold in 2020, with approximately 318,000 units.
- Online sales accounted for approximately 62.5% of 2021 sales.
- The Northeast accounted for approximately 57.2% of location-based 2021 sales.
- Women's Apparel had the highest average operating margin in 2021 at approximately 45.2%.

## Data Cleaning

The raw data was inspected for missing values, duplicate records, inconsistent values, and issues with table relationships.

The following issues were identified and addressed:

- No duplicate rows were found.
- Two `UNITS_SOLD` values were recorded as `***` and were treated as missing.
- Two `PRICE_PER_UNIT` values were missing.
- `Ootlet` was identified as a misspelling of `Outlet` and standardized.
- Four retailer IDs appeared more than once in the retailer table and contained conflicting retailer information.
- One retailer ID did not exist in the retailer table.
- Ambiguous retailer records were excluded from location and retailer-level analysis but retained for analyses where the product information remained reliable.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

## Files

- `TABLE_PRODUCTS_885.csv` — Product data
- `TABLE_RETAILER_885.csv` — Retailer and location data
- `TABLE_SALES_885.csv` — Sales transaction data

## How to Run

The analysis was developed in Google Colab.

To reproduce the analysis:

1. Open the notebook in Google Colab.
2. Upload the three CSV files if necessary.
3. Run the notebook cells from top to bottom.

## Author

Max Popp
