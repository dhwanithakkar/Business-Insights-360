# 📊 AtliQ Hardware - Power BI Analytics (Business-Insights-360)

## 🚀 Project Overview  
As AtliQ Hardware continues to expand, the company is integrating **Power BI** into its operations to drive **data-informed decision-making**. This project delivers valuable insights across **finance, sales, marketing, and supply chain**, helping stakeholders make strategic business decisions.  

## Objective
This report enables **data-driven decision-making**, providing valuable insights to support various scenarios. Additionally, it helps answer "why" questions based on the given context.

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

## Data Modelling
We have used the Snowflake schema. 
![Image](https://github.com/user-attachments/assets/f8243306-44cd-4f15-928d-fe40716d49c7)

## 📊 Dashboards Overview  
- **Home Page** – Central hub for seamless navigation.  
- **Finance** – Insights on Profit & Loss, top-performing customers & products.  
- **Sales** – Analysis of Net Sales, Gross Margin, and profitability trends.  
- **Marketing** – Performance breakdown by customer segments.  
- **Supply Chain** – Forecast accuracy assessment & risk evaluation.  
- **Executive** – High-level business metrics for strategic decision-making.

## Overview
![Image](https://github.com/user-attachments/assets/e63d8df5-2141-4ae8-8346-36c08ef199b8)

## Finance View
![Image](https://github.com/user-attachments/assets/c77fa940-4506-4df1-b599-bcfc7cfbcd31)

## Sales View
![Image](https://github.com/user-attachments/assets/33051f7f-af9e-4e4a-8f09-a62d8dc7c71d)

## Marketing View
![Image](https://github.com/user-attachments/assets/7356ee40-6c54-4da3-a9b6-5e22ffaad15b)

## Supply Chain View
![Image](https://github.com/user-attachments/assets/55a2f7b4-9d51-405d-9f60-e056744be0ee)

## Executive View
![Image](https://github.com/user-attachments/assets/bb5de172-1bbc-4c78-8f0b-c6aa04687a5d)

