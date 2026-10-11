# Advanture_Work-Dashboards-Project
AdventureWorks BI Dashboard   A Power BI Business Intelligence project analyzing sales, revenue, profit, and performance metrics for the AdventureWorks Bike Shop dataset. It showcases advanced data modeling, DAX calculations, and interactive dashboards that deliver actionable insights across territories, products, and time periods.
----------------------------------------------------------------------------------------------------------------------------------------------------------------

# AdventureWorks BI Dashboard

## 📊 Project Overview
A complete Business Intelligence project built using **Power BI**, designed to analyze and visualize sales, revenue, profit, and performance metrics for the AdventureWorks Bike Shop dataset.  
It demonstrates advanced data modeling, DAX calculations, and interactive dashboard design for actionable insights.

---

## 🚀 Features
- **Interactive Dashboards**: Overview, Products, Territories, Customers, Losses, Report for the lowest 20 products.
- **Dynamic Filters**: Year, Quarter, Year_Quarter, Year_Month, Day_Name, Category, Sub_Category, Territory, Country, Ship Method.
- **KPIs**: Revenue, Net Profit, Profit Margin %, Quota_Achievement%, #Orders, #Freight, #Tax, #Sales, #Gross_Sales, #Revenue.
- **Visuals**: Bar Charts, Line Charts, Maps, Donut Charts, Tables, Cards, Heatmaps.

---

## 🧠 Data Modeling
The star schema includes:
- **Fact Table**: `SalesOrder`
- **Dimension Tables**:  
  - `Dim_Products`  
  - `Dim_Customers`  
  - `Dim_SalesPerson`  
  - `Dim_SalesTerritory`  
  - `Dim_ShipMethod`  
  - `Dim_Date`
- **Measures Table**: Centralized DAX measures for KPIs and calculations.

---

## 🧩 DAX Measures 
All measures created in the **Measures_Table**:

- `#Orders Min/Subcategory`  
- `#Rev. by Customers`  
- `#Revenue Min/Category`  
- `#Sales Min/SalesPerson`  
- `Average Discount %`  
- `Average Order Value`  
- `Average Selling Price`  
- `Discount Impact %`  
- `Gross Sales`  
- `Net Profit`  
- `Net Profit Min/Product`  
- `Num. Customers`  
- `Num. Products`  
- `Num. SalesPersons`  
- `Profit Margin %`  
- `Profit Margin % Min/Product`  
- `Quota Achievement %`  
- `Sales by Territory`  
- `Total Cost`  
- `Total Discounts`  
- `Total Freight`  
- `Total Orders`  
- `Total Revenue`  
- `Total Sales`  
- `Total Tax`

---

## 📈 Dashboards
- **Overview Dashboard** → Company-wide KPIs and trends.  
- **Products Dashboard** → Gross Sales, Discounts, ASP, Product performance.  
- **Territory Dashboard** → Sales by Territory, Freight, Growth %, Map visuals.  
- **Customers Dashboard** → Customer retention, AOV, Top customers.  
- **Losses Dashboards** → Two reports:  
  1. **Losses Interactive Dashboard** (negative KPIs view)  
  2. **Losses 20 Products Report** (bottom 20 products table)

---

## 📉 Losses Interactive Dashboard
This dashboard highlights **negative KPIs** across products, categories, and territories.

- **Title:** Losses Interactive Dashboard  
- **Metrics:** Total Revenue, Gross Sales, Total Orders, Net Profit, Profit Margin %  
- **Filters:** Territory, Category_Name, Year_Month  
- **Insights:**  
  - Shows KPIs with minimum values (Revenue, Profit, Orders, Sales, Profit_Margin%).  
  - Highlights weak performance dimensions.  
  - Provides a quick view of loss drivers.

---

## 📉 Losses 20 Products Report
This report lists the **bottom 20 products** with negative Net Profit and margins.

- **Title:** Loss list for the bottom 20 products  
- **Columns:** Product Name, SubCategory, Category, Group, Territory, Ship Method, Year Quarter, Total Revenue, Gross Sales, Total Sales, Net Profit, Profit Margin %  
- **Insights:**  
  - Identifies specific products consistently incurring losses.  
  - Highlights territories and shipping methods contributing to negative margins.  
  - Summarizes total losses (e.g., Net Profit = -14,631.61, Margin = -1.06%).  

---

## 📂 Repository Structure

dventureWorks-BI-Dashboard/
│
├── PowerBI_Files/
│   └── AdventureWorks_Dashboard.pbix
│
├── Dashboards/
│   ├── Overview_Dashboard.png
│   ├── Products_Dashboard.png
│   ├── Territory_Dashboard.png
│   ├── Customers_Dashboard.png
│   ├── Losses_Interactive.png
│   └── Losses_20Products.png
│
└── README.md


---

## 👨‍💻 Author
**Mohamed Ayman Hassan**  
Data Analyst 
📧 Contact: [mohamedawaad290@gmail.com]  
🌐 LinkedIn: [www.linkedin.com/in/mohamed-ayman-7b3b031b1]

---

## 🏁 License
This project is for educational and portfolio purposes.  
Feel free to fork and explore improvements.

