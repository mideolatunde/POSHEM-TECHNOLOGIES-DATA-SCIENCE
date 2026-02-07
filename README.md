# Exploratory Data Analysis (EDA) – Poshem Business School Sales
## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a United States orders dataset to understand sales patterns, customer behavior, shipping performance, and data quality. The analysis uses Python in a Jupyter Notebook environment.

### Dataset Description
Source: United States sales transaction data

Timeframe: Approximately 1,457 days (~4 years) based on order date

Total Unique Orders: 4,922


### Data Cleaning
Identified 11 missing values in the Postal Code column, all associated with Burlington, Vermont (East).

No duplicate records were found in the dataset.

Date columns were converted to datetime format for temporal analysis.

### Exploratory Analysis Summary
Sales values exhibit a right-skewed distribution, with the mean exceeding the median and the presence of high-value outliers.

The West region records the highest number of orders, while the South region has the lowest.

New York City is among the top five cities by order volume and records the highest number of orders overall.

The dataset contains three product categories, with Technology generating the highest total sales.

Furniture has the highest median sales value, indicating higher spending per transaction.

Standard Class shipping is the most frequently used shipping mode and has the longest delivery duration, while Same Day shipping is least used and has a delivery time of zero days.

The Consumer segment accounts for the highest number of orders.

### Visualizations
The analysis includes:

Bar charts for regional and shipping mode distributions

Histograms, violin plots and box plots for sales distribution


### Tools and Libraries
Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook

Scipy

### Conclusion
The EDA reveals clear differences in customer behavior across regions, shipping modes, and product categories. Customers prioritize cost-efficient shipping options, sales are driven by a mix of high-volume low-value and low-volume high-value transactions, and purchasing patterns vary significantly by category and region.
