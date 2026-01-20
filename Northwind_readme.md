#  Northwind Traders Sales Dashboard

An interactive Excel dashboard analyzing sales performance, customer behavior, and product trends for Northwind Traders.

## Project Objective

To analyze 3 years of sales data (2013-2015) and create an interactive dashboard that provides actionable insights for business decision-making, including:
- Sales trends and seasonality patterns
- Top-performing products and customers
- Key performance indicators (KPIs) tracking

---

## Dataset

**Source:** Northwind Database (Sample Database)

**Tables Used:**
- `categories` - Product categories (8 records)
- `customers` - Customer information (91 records)
- `employees` - Employee data (9 records)
- `orders` - Order transactions (830 records)
- `order_details` - Line items per order (2,155 records)
- `products` - Product catalog (77 records)
- `shippers` - Shipping companies (3 records)

**Time Period:** July 2013 - May 2015

**Key Metrics:**
- Total Sales: $22,801,982
- Total Orders: 2,155
- Unique Customers: 91
- Countries : 21

---

## Tools & Technologies

- **Microsoft Excel** - Dashboard creation and data visualization
- **Power Query** - Data import and transformation
- **Pivot Tables** - Data aggregation and analysis
- **Excel Charts** - Data visualization (Line, Bar, Pie charts)

---

## Methodology

### 1. Data Import & Cleaning
- Imported 7 CSV files using Power Query
- Validated data integrity and handled missing values
- Standardized date formats and data types

### 2. Data Transformation
- Created calculated column: `TotalSales = quantity × unitPrice × (1 - discount/100)`
- Extracted time dimensions (Year, Month)

### 3. Data Analysis
- Built pivot tables for multi-dimensional analysis
- Calculated KPIs: Total Sales, Total Orders
- Identified top performers (products, customers, categories)
- Analyzed geographic distribution and seasonal trends

### 4. Dashboard Design
- Created interactive visualizations with slicers
- Designed clean, professional layout
- Implemented consistent color scheme and formatting
- Added dynamic filtering by year

---

## Key Insights

### Sales Performance
- **Peak Month:** significant upward trend starting in early 2014. Sales reached an all-time high in February 2015, peaking at $3,185,921.
- **Seasonal Pattern:** Strong Q4 performance, indicating holiday season impact
- **Growth Trend:** Fluctuating monthly sales with overall upward trajectory

### Product Analysis
- **Top Product:** Chang (156 Sold)
- **Best Category:** Beverages (23% of total sales)
- **Product Mix:** 77 products across 8 categories

### Customer Insights
- **Top Customer:** Hungry Owl All-Night Grocers ($2,447,261)
- **Customer Base:** 91 active customers across 21 countries

### Operational Metrics
- **Core Markets: ** Based on the Sales by Country pie chart, Austria, Germany, and France appear to be the most dominant markets in terms of sales volume
- **Order Volume:** 2,155 orders over 3 years

---

## Business Recommendations

Based on the analysis, here are key recommendations:

1. **Capitalize on Q4 Performance:** Increase inventory and marketing spend in Q4 to maximize holiday season sales

2. **Inventory Optimization::** Ensure that high-demand products like "Chang" and "Chai" are always in stock to avoid missing out on easy sales volume

3. **Customer Retention:** Implement loyalty program for top 4 customers who account for significant revenue

4. **Category Strategy:** Invest more in Beverages and (Meat & Poultry) categories given their strong performance

---


## Dashboard Features

### Interactive Components
- **Year Filter Slicer** - Filter data by 2013, 2014, or 2015
- **Dynamic KPI Cards** - Real-time updates based on filter selection

### Visualizations
1. **Sales Trend Line Chart** - Monthly sales performance over time
2. **Top Products Bar Chart** - Top 10 revenue-generating products
3. **Sales by Category Pie Chart** - Revenue distribution across categories
4. **Sales by Country Pie Chart** - Geographic revenue breakdown
5. **Top 10 Customers Table** - Ranked list of highest-value customers

---

## Contact Info

**Anugrah Seputra**
- LinkedIn: https://linkedin.com/in/anugrah-seputra-321169280
- Email: anugrahseputra93@gmail.com

---