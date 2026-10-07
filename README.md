# Superstore-Sales-Performance-Analysis

### Excel-based end-to-end analysis of product, category, region & segment performance with trend identification over time

## Project Overview / Purpose

This project analyses the performance of products, categories and sub-categories across different regions and customer segments.  
It also identifies sales & profit patterns and trends over months, years and weekdays using the classic Sample Superstore dataset.

**Business Goal:**  
Help stakeholders understand where the business is performing well, where it is under-performing, and which product/region/segment combinations drive (or destroy) profitability so that informed decisions can be made on inventory, discounts, shipping and marketing.

## Tech Stack

- **Microsoft Excel**
  - Pivot Tables & Pivot Charts
  - Advanced formulas (SUMIF, COUNTIF, AVERAGE, MIN/MAX, text functions, date functions, etc.)
  - Conditional formatting & data classification
  - Multiple interactive summary sheets

## Dataset

- **Source:** Sample Superstore dataset (classic Kaggle / Tableau sample)
- **Records:** 9,994 order line items
- **Time period:** 2014 – 2017
- **Key fields:** Order ID, Order/Ship Date, Customer, Segment, Region, Category, Sub-Category, Product, Sales, Quantity, Discount, Profit, Ship Mode, etc.
- **Additional sheets:** Returns, Regional Managers (People)

## Key Features & Highlights

### 1. Business Problem
Superstore generates strong revenue (~$2.3 M) but profit is only ~12.5% of sales.  
The analysis answers:
- Which categories, sub-categories and products are the real profit drivers?
- How do regions and customer segments differ in performance?
- What are the monthly / weekday seasonality patterns?
- Which products and customers are the top & bottom performers?
- How do shipping modes and discounts affect results?

### 2. Analysis Performed (Pivot Tables & Charts)
- **KPIs Dashboard** – Total Sales, Total Profit, Average Sales, Total Orders, Total Customers
- Sales & Profit by **Category** and **Sub-Category**
- Sales by **Region × Category** matrix
- Orders by **Ship Mode** and **Segment × Ship Mode**
- Contribution of each Ship Mode to every Region
- **Monthly** Sales & Profit trends
- **Weekday** Sales & Profit patterns
- Top 10 / Bottom 10 **Products**, **Customers** and **Orders**
- Minimum sales by Customer Segment
- Product quantity sold by Region
- Returns analysis

### 3. Key Insights (from the Pivot Tables)
| Metric                        | Value                  |
|-------------------------------|------------------------|
| Total Sales                   | $2,297,201             |
| Total Profit                  | $286,397               |
| Average Order Line Sales      | $229.86                |
| Total Orders                  | 9,994                  |
| Total Customers               | 793                    |

- **Technology** is the highest revenue category, followed by Furniture, then Office Supplies.
- **West** region leads in sales, followed by East → Central → South.
- **Standard Class** is by far the most used shipping mode.
- Strong seasonality: Sales and profit peak in **September–December**.
- Monday, Friday and Sunday show the highest sales among weekdays.
- A small number of products (especially certain copiers & machines) drive a disproportionate share of revenue.
- High discounts (>45%) are associated with many of the loss-making order lines.

### 4. Business Impact
The analysis highlights clear opportunities:
- Focus inventory and marketing on high-margin Technology products and the West/East regions.
- Review discounting policy – especially in the Central region and on certain Furniture items.
- Investigate why some high-sales products still generate losses.
- Leverage the strong Q4 seasonality and weekend/weekday patterns for promotional planning.

## Project Structure
📁 Superstore-Sales-Analysis
├── Sample - Superstore.xls          # Main analysis workbook
│   ├── Orders                       # Cleaned transactional data + calculated columns
│   ├── PivotTables&Charts           # All major pivot tables & charts
│   ├── KPI                          # Key Performance Indicators
│   ├── Report                       # Supporting summary
│   ├── Returns                      # Returned orders
│   ├── People                       # Regional managers
│   └── Practice                     # Formula practice & helper calculations
└── README.md                        # This file



## How to Use

1. Download / clone the repository.
2. Open `Sample - Superstore(1).xls` in Microsoft Excel (or compatible software).
3. Navigate through the sheets:
   - Start with **KPI** for the big picture.
   - Explore **PivotTables&Charts** for detailed breakdowns.
   - Use the **Orders** sheet for raw data and calculated flags.

## Author

DARSHAN R  
Data Analyst | Excel | Power BI | SQL  

---

*This project demonstrates strong Excel skills in data cleaning, Pivot Table design, business metric calculation and insight generation – exactly the kind of work expected from a Business / Data Analyst role.*
