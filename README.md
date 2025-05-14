# 🛒 Superstore Sales Analysis – Python Project

## 📊 Overview  
This data analysis project investigates a Superstore's sales data using Python. The goal is to explore key metrics such as **product performance**, **sales trends**, **region-wise contribution**, and **category breakdown**. Visualizations are used to highlight insights that can support data-driven business decisions.

---

## 🎯 Project Objective  
To perform exploratory data analysis (EDA) on a retail dataset in order to:

- Identify the most profitable products and categories  
- Analyze sales trends by region, date, and segment  
- Visualize patterns in customer purchase behavior  
- Generate insights to support marketing and inventory strategies

---

## 🔄 Process

### 1. Data Import & Setup  
- Loaded Excel file (`superstore_sales.xlsx`) using `pandas`  
- Imported libraries: `numpy`, `matplotlib`, `seaborn`, `plotly.express`

### 2. Data Cleaning  
- Verified data types and handled missing values  
- Parsed `Order Date` to datetime format  
- Renamed and standardized column names where needed

### 3. Feature Exploration  
- Grouped and analyzed:
  - Total sales by `product_name`, `category`, and `region`  
  - Order quantity and profit trends  
  - Monthly/yearly sales volumes

### 4. Data Visualization  
- Created charts using `matplotlib`, `seaborn`, and `plotly`:
  - Top 5 products by sales  
  - Sales by region and category  
  - Line chart of monthly sales trend  
  - Profit distribution across segments

---

## 🗃️ Data Details

### Dataset Fields Used  
- `product_name` – Name of the product sold  
- `category` – Product category (Furniture, Office Supplies, etc.)  
- `region` – Sales region  
- `sales`, `profit`, `quantity` – Performance metrics  
- `order_date`, `customer_segment` – Time & customer grouping

---

## 📈 Analysis Highlights

### 🥇 Top Products  
- Identified top 5 best-selling products  
- Helped recommend stock prioritization

### 🌎 Regional Insights  
- Analyzed sales by region and highlighted high/low performing areas  
- Visualized regional patterns with bar charts

### 📅 Time Trends  
- Monthly and yearly trends showed peak sales periods  
- Useful for planning seasonal campaigns and promotions

---

## 💡 Key Insights

- Some products contribute disproportionately to total sales  
- Profitability does not always align with sales volume  
- Office Supplies category performs steadily across all regions  
- Western region shows the highest revenue but moderate profit margins

---

## 📌 Recommendations

1. **Promote Top-Selling Products**  
   Focus marketing efforts on the top 5 revenue-driving products.

2. **Region-Specific Strategies**  
   Use targeted campaigns in underperforming regions.

3. **Review Low-Profit Items**  
   Investigate why high-selling products may have low profitability.

4. **Seasonal Planning**  
   Leverage monthly trends to optimize stock levels and staffing.

---

## ✅ Conclusion  
This project showcases strong skills in:

- ✅ Data importing, cleaning, and transformation with `pandas`  
- ✅ Grouping and aggregation to derive business metrics  
- ✅ Interactive and static visualizations using `plotly` and `seaborn`  
- ✅ Delivering business insights from retail data

---

## 🛠️ Tools Used  
- Python 3.x  
- Jupyter Notebook  
- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- `plotly.express`

---

## 📎 Files Included  
- `sales.ipynb` – Full notebook with analysis and plots  
- `superstore_sales.xlsx` – Dataset used for analysis *(optional in repo)*

---
