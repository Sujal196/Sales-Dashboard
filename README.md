## Sales Analytics Dashboard (Power BI)

### Dashboard Link

*(To be updated after Power BI Service publication)*

---

## 1. Business Objective

The **Sales Analytics Dashboard** is designed to provide senior management and business stakeholders with a consolidated, interactive view of sales performance across products, cities, promotions, and time periods. The primary goal of this dashboard is to enable **data-driven decision-making** by identifying revenue drivers, profit leakages, customer demand patterns, and promotional effectiveness.

This report supports strategic planning, operational monitoring, and performance evaluation by answering key business questions such as:

* Which products and cities are driving the highest and lowest sales and profit?
* How are sales trending over time across different granularities?
* What is the relationship between sales volume and profitability?
* How effective are discounts and promotions in driving net sales?

---

## 2. Dataset Overview

The dataset contains transactional sales data with attributes including:

* Order Date
* Product Name
* City
* Quantity Sold
* Gross Sales
* Discount
* Net Sales
* Profit
* Promotion Category
* Order ID

The data was sourced from structured flat files and loaded into **Power BI Desktop** for transformation, modeling, and visualization.

---

## 3. Data Preparation & Modeling (Power Query)

* Data loaded into Power BI Desktop
* Column profiling enabled (column distribution, quality, and profile)
* Data types validated for date, numeric, and categorical fields
* Null and duplicate records checked and handled appropriately
* Calculated columns and measures created using DAX
* Star schema implemented for optimized performance

---

## 4. Key Performance Indicators (KPIs)

The following KPIs are displayed prominently at the top of the dashboard to provide an executive snapshot:

* **Total Sales** – Sum of gross sales value
* **Net Sales** – Sales after discount deductions
* **Total Units Sold** – Aggregate quantity sold
* **Total Orders** – Distinct count of Order IDs
* **Total Profit** – Overall profitability of sales

**Visual Used:** Card visuals

**Image Reference:**
![KPI Cards]()


---

## 5. Top & Bottom Product Performance

### Top 5 and Bottom 5 Products by:

* Sales
* Quantity Sold
* Profit

These visuals help identify high-performing and underperforming products, enabling inventory optimization and pricing strategy adjustments.

**Visual Used:** Clustered bar charts with Top N filtering

**Image Reference:**
![Top Bottom Products](https://via.placeholder.com/900x400?text=Top+and+Bottom+Products+by+Sales+Profit+Quantity)

---

## 6. Sales Trend Over Time

Sales trends are analyzed across multiple time granularities:

* Daily
* Monthly
* Quarterly
* Yearly

This allows stakeholders to identify seasonality, growth patterns, and performance fluctuations over time.

**Visual Used:** Line chart with date hierarchy

**Image Reference:**
![Sales Trend](https://via.placeholder.com/900x400?text=Sales+Trend+Over+Time)

---

## 7. Relationship Between Sales and Profit

A scatter plot is used to analyze the correlation between sales and profit at the product level. This visualization helps identify:

* High sales but low profit products
* Premium high-margin products
* Products requiring cost or pricing optimization

**Visual Used:** Scatter chart (Sales vs Profit)

**Image Reference:**
![Sales vs Profit](https://via.placeholder.com/900x400?text=Sales+vs+Profit+Relationship)

---

## 8. Average Discount by Promotion Category

This section evaluates promotional effectiveness by calculating the **average discount offered** under each promotion category. It helps marketing teams understand discount intensity and its potential impact on margins.

**Visual Used:** Column chart

**Image Reference:**
![Average Discount](https://via.placeholder.com/900x400?text=Average+Discount+by+Promotion+Category)

---

## 9. Net Sales by City and Product

A geographical and product-level breakdown of **Net Sales** is provided to understand regional demand and city-wise performance.

**Visuals Used:**

* Map visual (City-wise Net Sales)
* Table / Matrix (Product-wise Net Sales)

**Image Reference:**
![Net Sales by City](https://via.placeholder.com/900x400?text=Net+Sales+by+City)

![Net Sales by Product](https://via.placeholder.com/900x400?text=Net+Sales+by+Product)

---

## 10. Sales Information Drill-Through Dashboard

A detailed sales information view allows users to drill down to the **order level**, showing:

* Sales
* Profit
* Discount
* Net Sales
* Quantity

Interactive slicers are provided for:

* Product Name
* Date
* Customer ID
* Promotion Category

This ensures complete transparency and self-service analytics for business users.

**Image Reference:**
![Sales Details](https://via.placeholder.com/900x400?text=Sales+Information+Dashboard)

---

## 11. Interactivity & Filters

* Cross-filtering enabled across all visuals
* Date slicer for period comparison
* Product, city, and promotion category filters
* Tooltip insights for enhanced user experience

---

## 12. Key Business Insights

* Top products contribute a significant share of total revenue, while bottom products highlight optimization opportunities
* Seasonal trends impact monthly and quarterly sales performance
* High sales do not always translate to high profit, indicating pricing or discount inefficiencies
* Certain promotion categories drive volume but reduce margins
* Urban cities contribute the highest net sales

---

## 13. Conclusion

The **Sales Analytics Power BI Dashboard** delivers a comprehensive, scalable, and executive-ready analytics solution. It empowers stakeholders with real-time insights, improves decision accuracy, and supports revenue growth and profitability optimization through data-backed strategies.

---

*Prepared by: Power BI Analytics Consultant*
*Tool Used: Microsoft Power BI*
