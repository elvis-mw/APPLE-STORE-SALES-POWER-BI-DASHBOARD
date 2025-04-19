
# 🍏 Apple Store Dashboard – Power BI Project

## 📊 Project Summary

This Power BI dashboard delivers a detailed analysis of Apple Store operations, including product sales, warranty claims, product categories, and store performance. It is designed to support data-driven decision-making for sales, operations, and product management teams.

---

## 📂 Included Datasets

| Dataset      | Description |
|--------------|-------------|
| **Sales**    | Transactional data with revenue, quantity, product ID, store ID, and date of sale |
| **Warranty** | Warranty claims by product, store, status, and claim date |
| **Products** | Metadata such as product name, price, launch date, and ID |
| **Categories** | Product groupings like iPhones, iPads, MacBooks, etc. |
| **Stores**   | Location and regional data for each Apple Store |

---

## 🎯 Dashboard Goals

- Track sales trends and revenue over time
- Identify high-performing products and categories
- Analyze warranty claims to uncover quality issues
- Compare performance across stores and regions
- Provide dynamic, interactive filtering capabilities

---

## 📈 Key Features

- **KPIs**: Total Revenue, Units Sold, Average Price, Warranty Rate  
- **Sales Trends**: Monthly and quarterly revenue tracking  
- **Product & Category Insights**: Sales by item and category  
- **Warranty Analysis**: Claims over time, by store and product  
- **Store Performance**: Region-wise performance comparison with maps and visuals  
- **Filters & Slicers**: By category, store, date, warranty status  

---

## 🧠 Sample DAX Measures

```DAX
Total Sales = SUM(Sales[Revenue])
Units Sold = SUM(Sales[Quantity])
Average Price = [Total Sales] / [Units Sold]
Total Claims = COUNT(Warranty[ClaimID])
Warranty Rate = [Total Claims] / [Units Sold]
```

---

## 🔗 Data Model

The model follows a **star schema**:
- Fact Tables: `Sales`, `Warranty`
- Dimension Tables: `Products`, `Categories`, `Stores`

Relationships are defined via primary keys such as `ProductID` and `StoreID`.

---

## 🛠 Tools Used

- **Power BI Desktop** – for report creation and visualization
- **Power Query** – for data transformation and cleaning
- **DAX** – for custom measures and KPIs

---

## 🚀 How to Use

1. Open the `Apple Store Power BI Report.pbix` file in Power BI Desktop.
2. Use filters and slicers to explore data from different angles.
3. Refresh data or modify visuals as needed for custom analysis.

---

## 📬 Contact

Created by **[Your Name]**  
📧 Email: [your.email@example.com]  
🔗 LinkedIn: [Your LinkedIn Profile]  
🌐 Portfolio: [Optional]

---
