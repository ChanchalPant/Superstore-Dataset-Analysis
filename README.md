# Analysis of US Superstore Dataset

## Overview
This dataset pertains to a superstore in the US, providing information on customer transactions from 2014 to 2017. The data was sourced from Kaggle in CSV format.

## Data Preparation
- Identified and removed a duplicate transaction record for the customer Laurel Beltran using the "remove duplicate" function.
- Deleted the unnecessary "Row ID" column, as each row already had a unique ID assigned by Excel.
- Changed the data type of order date and ship date from text to date, adjusting the date format.
- Converted sales and profit columns to accounting format for clarity.
- Calculated shipping duration by finding the difference between Order date and Ship date using Excel's DAYS function.

## Data Analysis and Visualization
I utilized Pivot tables and charts to organize and summarize the data, leading to the following insights:

### Sales Analysis
- **City and State with Highest Sales:**
  - New York City: $256.37K
  - Los Angeles: $175.85K

- **States with Highest Sales:**
  - California: $457.69K (20% of total sales)
  - New York: $310.88K (14% of total sales)

- **Regional Sales Contribution:**
  - West region: 32% of total sales
  - South region: 17% of total sales

### Shipping Preferences
- **Shipping Modes:**
  - Standard class: 60% of total instances
  - Same day: 5% of total instances

### Product Categories
- **Top Product Categories:**
  - Technology: 37% of total sales ($836.15K)
  - Office supplies: 31% of total sales ($719K)

### Customer Insights
- **Top Spending Customers:**
  - Sean Miller: $25.04K
  - Tamara Chand: $19.05K

### Product Performance
- **Top Selling Product:**
  - Canon imageCLASS 2200 Advanced Copier

### Sales Trends
  - Steady increase in sales each year.
  - Slight drop in 2015 compared to 2014, followed by steady growth.

## Summary
The data analysis offers valuable insights into sales, shipping preferences, product categories, and customer spending for the superstore.
