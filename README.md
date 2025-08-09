#  RetailPulse – Sales Performance & Customer Insights Dashboard  

**Project Lead:** Neha Gupta  
**Team Member:** Devisha Kumari  

An end-to-end **Power BI analytics project** built using the [Kaggle Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final), designed to uncover **sales trends, profit drivers, and customer behavior** across regions.  
This project demonstrates **data preparation, star schema modeling, advanced DAX, and interactive dashboarding** for executive-level decision-making.

---

##  Dataset Overview
**Source:** Kaggle – Superstore Dataset (Retail)  

**Key Fields:**
- **Orders:** Order ID, Order Date, Ship Date  
- **Customers:** Customer ID, Name, Segment  
- **Products:** Category, Sub-Category  
- **Sales Metrics:** Sales, Quantity, Discount, Profit  
- **Location:** Region, State, City, Postal Code  
- **Logistics:** Shipping Mode  

A clean, relational dataset — ideal for **data modeling** and **business intelligence dashboards**.

---

##  Objective
To provide **actionable business insights** by:
- Identifying top-performing products, customers, and regions  
- Analyzing time-based trends in sales & profitability  
- Measuring the impact of discounts on profit  
- Enabling **role-based, region-specific insights** using RLS  

---

##  Project Workflow

### **1. Data Preparation (Power Query)**
- Removed unnecessary rows and cleaned column values  
- Corrected data types & renamed columns  
- Split/Merged fields (e.g., Customer Name)  
- Appended/Merged queries to integrate returns data  

### **2. Data Modeling**
- Implemented **Star Schema**:
  - Fact Table: Sales Orders  
  - Dimension Tables: Customers, Products, Regions, Dates  
- Defined **One-to-Many** & **Many-to-One** relationships  
- Managed Model View for clean design  

### **3. DAX Calculations**
- **Basic Measures:**
  - Total Sales
  - Total Profit
  - Distinct Customers
  - Average Discount
- **Time Intelligence:**
  - Year-to-Date (YTD), Month-to-Date (MTD), Quarter-to-Date (QTD)
  - Year-over-Year comparisons
- **Advanced Metrics:**
  - Customer contribution to total sales
  - % Sales by Region using iterators (`SUMX`, `AVERAGEX`)

### **4. Row-Level Security (RLS)**
- Role-based filtering to restrict access by region

### **5. Dashboard Design**
- KPI Cards: Sales, Profit, Customer Count  
- Top Cities, Top Customers  
- Sales & Profit trend lines  
- Regional performance heatmaps  
- Slicers for Segment, Region, Product Category  
- Drilldowns, bookmarks, and a clean corporate theme  

---

##  Key Insights
- **Region Performance:** Clear leaders and underperformers identified  
- **Profitability Impact:** Discounts >20% significantly erode profit margins  
- **Customer Analysis:** Repeat customers contribute a high share of total revenue  
- **Seasonality:** Quarterly spikes observed in specific regions  

---

##  Tools & Technologies
- **Power BI** – Data Modeling, Visualization, DAX  
- **Power Query** – Data Cleaning & Transformation  
- **Excel/CSV** – Data Source  

---

##  Business Value
The **RetailPulse Dashboard** enables:
- Quick identification of profitable segments  
- Targeted sales strategies per region  
- Monitoring of discount policies’ financial impact  
- Better resource allocation based on customer and product trends  
ial impact  
- Better resource allocation based on customer and product trends
