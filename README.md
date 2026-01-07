## Sales-Dashboard 

### Dashboard Link : *(To be updated after Power BI Service publication)*

## Problem Statement 

This dashboard helps the organization understand its sales performance, profitability and customer demand patterns across products, cities and promotional categories. It enables business stakeholders to identify top and bottom performing products, evaluate the impact of discounts and promotions and track sales trends over time to support informed strategic and operational decisions.

Through key performance indicators such as total sales, net sales, total units sold, total orders and total profit, decision-makers gain a consolidated view of overall business health. Additionally, by analyzing the relationship between sales and profit, the organization can identify margin leakages caused by excessive discounting or inefficient pricing strategies.

Since profitability does not always grow proportionally with sales, this dashboard highlights such gaps and enables corrective actions through product rationalization, promotion optimization and regional performance analysis.


## Dataset Overview

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

The data was sourced from structured flat files and loaded into **Power BI Desktop** for transformation, modeling and visualization.

## Steps Followed

* Step 1 : Loaded sales data into Power BI Desktop from structured flat files (CSV format).
* Step 2 : Opened Power Query Editor and enabled column distribution, column quality and column profile under the Data Preview section.
* Step 3 : Enabled column profiling based on the entire dataset instead of the default 1000 rows.
* Step 4 : Validated data types for sales, quantity, discount, profit and date fields; handled null and duplicate values where applicable.
* Step 5 : Created calculated columns and DAX measures for Net Sales, Total Orders, Total Units Sold and Profit metrics.
* Step 6 : Applied a consistent report theme to ensure a professional and stakeholder-ready layout.
* Step 7 : Added KPI card visuals representing Total Sales, Net Sales, Total Units Sold, Total Orders and Total Profit.
* Step 8 : Created bar charts to display Top 5 and Bottom 5 products by Sales, Quantity Sold and Profit using Top N filters.
* Step 9 : Added a line chart with date hierarchy to analyze sales trends over daily, monthly, quarterly and yearly levels.
* Step 10 : Used a scatter plot to visualize the relationship between Sales and Profit, highlighting high-revenue but low-margin products.
* Step 11 : Created a column chart to show average discount by promotion category.
* Step 12 : Added a map visual to represent Net Sales by City and a matrix to show Net Sales by Product Name.
* Step 13 : Built a detailed Sales Information Dashboard displaying Sales, Profit, Discount, Net Sales and Quantity at the order level.
* Step 14 : Added slicers for Product Name, Date, Customer ID and Promotion Category to enable interactive filtering.
* Step 15 : Published the report to Power BI Service for stakeholder access.


## Key Performance Indicators

The following KPIs are displayed prominently at the top of the dashboard to provide an executive snapshot:

* Total Sales – Sum of gross sales value
* Net Sales – Sales after discount deductions
* Total Units Sold – Aggregate quantity sold
* Total Orders – Distinct count of Order IDs
* Total Profit – Overall profitability of sales

* Visual Used: Card visuals

![KPI Cards](https://github.com/user-attachments/assets/a81ba408-07ca-4358-bb73-06e1155540f9)


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
