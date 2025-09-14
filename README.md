# Power BI Sales Analytics Dashboard

## 📌 Project Overview
This project demonstrates a **Retail Sales Analytics Dashboard** built in **Power BI**.  
The goal is to analyze customer behavior, product performance, and sales trends across regions and time.

## 🗂 Dataset
The model follows a **star schema** with one fact table and three dimension tables:

- **Customers** → CustomerID, Name, Region, AgeGroup  
- **Products** → ProductID, Category, SubCategory, Price  
- **Date** → DateID, Date, Month, Quarter, Year  
- **Sales (Fact)** → SaleID, CustomerID, ProductID, DateID, Quantity, SalesAmount  

## 🔗 Relationships
- Sales → Customers (CustomerID)  
- Sales → Products (ProductID)  
- Sales → Date (DateID)  

## 📊 Dashboard Features
- **KPIs**: Total Sales, Total Customers, Average Order Value  
- **Charts**:
  - Sales by Region  
  - Sales Trend over Time  
  - Top Products by Sales  
  - Customer Age Group Analysis  
- **Slicers/Filters**: Region, Category, Year  

## 🚀 Next Steps
- Build Power BI dashboard using these CSV files  
- Publish screenshots of the dashboard in `/docs` folder  
- Optimize model with measures, relationships, and filters  

---
⭐ This project highlights **data modeling, DAX, and visualization skills** relevant to analytics & reporting roles.# PowerBI_Analytics
