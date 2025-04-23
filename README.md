
### **Project Title: Super Store Sales Dashboard Using Power BI**

The **Super Store Dashboard project** is a comprehensive data analysis and business intelligence solution developed using **Microsoft Power BI**. The goal of this project is to transform raw sales data into actionable insights through dynamic dashboards that highlight sales performance, regional trends, product profitability, and customer behavior. Designed for decision-makers, this interactive dashboard empowers users to monitor key performance indicators (KPIs) and make data-driven strategic decisions to improve business operations, optimize inventory, and enhance profitability.

---

### 🧭 **Project Objectives:**

- To analyze sales, profit, and quantity metrics across categories, regions, and time  
- To provide visual insights into customer segments and order trends  
- To build a user-friendly, interactive dashboard that enables dynamic filtering and drill-down analysis  
- To support executives and managers in making informed business decisions

---

### 🧰 **Tools and Features Used:**

- **Power BI Desktop** – For data modeling, transformation, and dashboard creation  
- **Power Query Editor** – For data cleaning, merging, and preprocessing  
- **DAX (Data Analysis Expressions)** – For creating calculated columns, measures, and KPIs  
- **Power BI Service** – For publishing and sharing reports online (if applicable)  
- **Slicers and Filters** – For enabling interactive selections (by Region, Category, Date, etc.)  
- **Drill-through & Tooltip Pages** – For providing deeper insights on visual click  
- **Custom Visuals & Charts** – For enhancing the dashboard interface

---

### 📊 **Data Sources & Preprocessing:**

The dataset typically includes details such as:
- Order ID, Order Date, Ship Date  
- Customer Name, Segment, Region, and State  
- Product Category and Sub-Category  
- Sales, Quantity, Discount, and Profit  
- Shipping mode and delivery status

**Key preprocessing steps:**
- Removing duplicates and blanks  
- Creating a proper date hierarchy  
- Standardizing category names and region entries  
- Generating new columns for **Year**, **Month**, and **Quarter** from Order Date  
- Creating DAX measures for **Total Sales**, **Total Profit**, **Profit Margin**, and **Average Order Value**

---

### 📈 **Visuals and Dashboards Created:**

- **KPI Cards** for Total Sales, Total Profit, Orders, and Profit Margin  
- **Bar & Column Charts** showing sales by Product Category, Sub-Category, and Region  
- **Line and Area Charts** to display time-based trends across months and years  
- **Donut/Pie Charts** to visualize customer segments and market share  
- **Tree Maps** for highlighting top-performing products  
- **Heat Maps & Matrix Tables** to analyze performance by Region vs. Category  
- **Geo Maps** for state-wise and regional sales distribution  
- **Slicers** for filtering data by Segment, Region, Year, and Product Category

---

### 💡 **Key DAX Measures Created:**

- `Total Sales = SUM(Sales)`  
- `Total Profit = SUM(Profit)`  
- `Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))`  
- `Avg Order Value = DIVIDE(SUM(Sales), COUNTROWS(Orders))`  
- `YTD Sales = TOTALYTD([Total Sales], Date[Order Date])`  
- `Sales Growth % = DIVIDE([This Year Sales] - [Last Year Sales], [Last Year Sales])`

---

### ✅ **Key Insights & Business Impact:**

- The **West Region** generated the highest revenue, while the **South** showed the most consistent growth.  
- **Technology** and **Office Supplies** were the top-performing categories in terms of both sales and profit.  
- **Furniture**, though generating good revenue, had a lower profit margin due to higher discounts and costs.  
- The **Corporate Segment** contributed the highest share to total profit, despite fewer orders compared to the Consumer Segment.  
- Seasonal trends showed spikes in sales during **Q4**, indicating promotional opportunities during holidays.  
- Geo-mapping revealed untapped markets in certain states with low customer penetration.


