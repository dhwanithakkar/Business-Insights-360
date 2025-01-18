# 📊 AtliQ Hardware - Power BI Analytics (Business-Insights-360)

## 🚀 Project Overview  
As AtliQ Hardware continues to expand, the company is integrating **Power BI** into its operations to drive **data-informed decision-making**. This project delivers valuable insights across **finance, sales, marketing, and supply chain**, helping stakeholders make strategic business decisions.  

## 📊 Data & Analytics Tools
- **SQL** – Data extraction, transformation & management  
- **Power BI Desktop** – Dashboard creation & data visualization  
- **Excel** – Data preprocessing & organization  
- **DAX (Data Analysis Expressions)** – Advanced calculations & measures  
- **DAX Studio** – Query optimization for performance  
- **Project Charter File** – Planning & documentation

## 🔍 Key Features  
✔️ **Dynamic dashboards** for real-time insights  
✔️ **Optimized DAX queries** to enhance performance  
✔️ **End-to-end business reporting** across multiple functions

## 📌 Power BI Techniques Learned  

- **Project Planning & Requirements Gathering** – Key questions to ask before starting  
- **Data Modeling** – Structuring data for optimal performance  
- **Calculated Columns & Measures** – Creating insights using DAX  
- **DAX Functions** – Implementing advanced calculations  
  - `DIVIDE()` function to prevent division by zero errors  
  - Creating **date tables** using M language  
- **Visualization Enhancements**  
  - Dynamic titles based on applied filters  
  - Conditional formatting with icons & background colors  
  - KPI indicators for performance tracking  
  - Using **Bookmarks** to toggle between visuals  
  - **Page Navigation** with buttons  
- **Power BI Service & Deployment**  
  - Publishing reports to **Power BI Service**  
  - Setting up **Personal Gateway** for automatic data refresh  
  - Creating & managing **Power BI Apps**  
  - Collaboration through **Workspaces & Access Permissions**
 

# 📊 Dataset Overview  
NOTE: Imported the datasets from Mysql database to PowerBI

This dataset consists of **dimension tables** (static data) and **fact tables** (transactional data).  

### 🗂 Dimension Tables (Reference Data)  
- **`dim_customer`** – 75 customers across 27 markets, 3 sales channels (Retailer, Direct, Distributors), 2 platforms (E-commerce, Brick & Mortar).  
- **`dim_market`** – 27 markets, 7 sub-zones, 4 regions (APAC, EU, NAN, LATAM).  
- **`dim_product`** – 14 product categories across **Peripherals & Accessories** and **Networking & Storage**.  

### 📊 Fact Tables (Transactional Data)  
- **`fact_forecast_monthly`** – Forecasted customer demand, aiding in inventory & cost management.  
- **`fact_sales_monthly`** – Similar to forecast table but with actual sales data.  

### 💰 Cost & Financial Data  
- **`freight_cost`** – Logistics costs by market & fiscal year.  
- **`gross_price`** – Product pricing details.  
- **`manufacturing_cost`** – Production cost data.  
- **`pre_invoice_deductions` & `post_invoice_deductions`** – Various cost adjustments.  

