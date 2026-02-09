# Exploratory Data Analysis (EDA) – Poshem Business School Sales

## &#128279; Project Overview
This project presents an Exploratory Data Analysis (EDA) on Poshem Business School Sales dataset to understand order & sales patterns, customer behavior, shipping performance in the United States within 4 years. It is conducted as part of the **Poshem Technologies Institute Python Data Challenge**. 

## &#128279; Authors
* Ayomide Olatunde

## &#128279; Table of Contents
* [Authors](#-authors)
* [Table of Contents](#-table-of-contents)
* [Project Objectives](#-project-objectives)
* [Dataset Description](#-dataset-description)
* [Tools & Technologies Used](#-tools--technologies-used)
* [Data Cleaning](#-data-cleaning)
* [Analysis Questions](#-analysis-questions)
* [Key Insights](#key-insights)
* [Visualizations](#visualizations)
* [Learning Outcomes](#learning-outcomes)
* [How to Run the project](#how-to-run-the-project)
* [Repository Structure](#repository-structure)
* [License](#license)
* [Contact](#contact)

## &#127919; Project Objectives
1. Conduct extensive EDA on Poshem Business School Sales data.
2. Perform structured data cleaning and analysis.
3. Identify trends and patterns in customer behaviour for different regions, cities, segments.
4. Create multiple visualisation.
5. Understand the overall distribution of the data.
6. Derive insights.

### &#128194; Dataset Description
- **Source**: Poshem Business School sales data
- **Timeframe**: January 2015 - December 2018 (Approximately 1,457 days (~4 years))
- **Records**: 9,800 entries
- **Columns**: 18

The dataset contains the following information:
- **Order Information**: Order ID, Order Date, Ship Date, Ship Mode
- **Customer Data**: Customer ID, Customer Name, Segment
- **Geographic**: Country, City, State, Postal Code, Region
- **Product Details**: Product ID, Category, Sub-Category, Product Name
- **Financial**: Sales

## &#128736; Tools & Technologies Used

#### **Programming Language** : `Python 3.10+` 

#### Libraries
- `pandas` – Data manipulation & cleaning

- `numpy` - Numerical analysis

- `matplotlib & seaborn` – Data Visualization

#### Environment
- `Jupyter Notebook` - Interactive analysis & documentation

- `github`

## &#129529; Data Cleaning

The following steps were performed before analysis:

* Remove missing values

* Ensured correct data types

* Handled duplicate records (No duplicate records were found in the dataset.)

* Prepared data for visualization-ready analysis

## 📈 Analysis Questions

The notebook is organized based on the following questions:

### 1. Overview
- Dataset timeframe
- Data structure (rows/columns)
- Missing values identification and correction
- Data types validation
- Duplicate detection
- Statistical summary

### 2. Order Statistics
- Unique orders count
- Order status distribution (Note: column not available in dataset)
- Customer count and retention metrics

### 3. Geographical Insights
- Country analysis
- Regional distribution
- Top 5 cities by order volume

### 4. Product Analysis
- Product categories overview
- Sales by category
- Top 5 selling products

### 5. Customer Segmentation
- Segment distribution
- Average order value by segment
- Customer behavior patterns

### 6. Shipping Operations
- Shipping modes analysis
- Delivery time analysis
- Regional shipping patterns

### 7. Sales Distribution
- Overall sales distribution
- Outlier detection (IQR method)
- Sales distribution by category

### 8. Profit Analysis
- **Note**: Profit data not available in dataset
- Alternative sales-based analysis provided
- Recommendations for future data collection


## 🔍Key Insights

### Market Performance
- **Total Revenue**: $2.3 million over 4 years, increase in total revenue over the years
- **Customer Base**: 793 unique customers
- **Order Volume**: 4922 unique orders
- **Average Order Value**: $230.77

### Geographic Insights
- **Top Regions**: West and East dominate with the highest orders
- **Growth Opportunity**: South region with the least number of orders
- **Urban Concentration**: Top 5 cities are New York City, Los Angeles, Philadelphia, San Francisco and Seattle

### Customer Segmentation
- **Consumer Segment**: 52% of orders (volume leader)
- **Corporate Segment**: approximately 30% of orders
- **Home Office**: Highest average order value `($243)`

### Product Performance
- **Technology**: $836K revenue (36.4%)
- **Furniture**: $742K revenue (32.3%)
- **Office Supplies**: $719K revenue (31.3%)

### Data Quality Issues Identified & Resolved
- Fixed 11 missing postal codes (Burlington, Vermont (East) = 05405)
- No duplicate records
- **Profit data unavailable** (limitation for profitability analysis)

## &#128200; Visualizations
The analysis includes:

- Several Bar charts showing the distribution of orders across different regions, top 5 cities with the highest orders, top 5 product categories according to sales, top 5 selling products based on the number of orders, average order value per customer segment.
- Box plot showing the distribution of shipping orders at different times
- Bar chart showing the shipping mode patterns per region
- Histogram showing the overall distribituion of Sales
- Violin plot showing the distribution of sales per category 


## &#128161; Learning Outcomes
Through this project, I demonstrated proficiency in:

#### Technical Skills
- Data cleaning, analysis and preprocessing
- Exploratory data analysis techniques
- Statistical analysis and interpretation
- Data visualization (Matplotlib, Seaborn)
- Python programming for data science
- Jupyter Notebook documentation

#### Soft Skills
- Effective communication
- Problem solving
- Teamwork
- Professional report writing

#### Tools Mastered
- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Data Visualization enhances clarity and business decision-making
- Statistical analysis methods

## &#128640; How to Run the Project
1. **Python Installation** (3.8 or higher)
```windows cmd
py -m python --version
```

2. **Required Libraries**
```windows cmd
py -m pip install pandas numpy matplotlib seaborn scipy jupyter lab
```

#### Step-by-Step Instructions

1. **Clone/Download Repository**
- Download the project folder
- Ensure all files are in the same directory

2. **Launch Jupyter Notebook**
```windows cmd
py -m jupyter lab
```

3. **Open the Notebook**
- Open `poshem_business_school_sales.ipynb` In Jupyter.

4. **Run all cells at once or Run cells individually**

#### Troubleshooting

**Issue**: "File not found" error
**Solution**: Ensure `poshem_business_school_sales.csv` is in the same directory as the notebook.

**Issue**: Import errors
**Solution**: Install missing libraries using `py -m pip install [library-name]`


## &#128193; Repository structure
```
Poshem_Sales_Project/
├──charts/ # Visualization charts
 ├── avg_order_value.png
 ├── dist_of_orders_across_diff_regions.png
 ├── dist_of_sales_per_categ.png
 ├── overall_distribution_of_sales.png
 ├── shipping_date_vs_shipping_mode.png
 ├── shipping_mode_per_region.png
 ├── top_5_cities.png
 ├── top_5_selling_products.png
 ├── top_product_categories.png
├── Poshem Business School Sales Project.pdf
├── Poshem Business School Sales.ipynb # Main analysis notebook
├── README.md # README
└── poshem_business_school_sales.csv # Dataset
```

## &#128110; License
This project was completed as part of the **Poshem Technologies Institute curriculum**.
Dataset provided by **Poshem Business School**.

## &#128222; Contact
**Email**: ayomideeli2002@gmail.com
**LinkedIn**: https://linkedin.com/in/ayomide-olatunde-2859141a8
**GitHub**: https://github.com/mideolatunde

**Institution**: Poshem Technologies Institute
**Course**: Python Data Challenge
**Project Supervisor**: Simon E. Akhamie, CEO



