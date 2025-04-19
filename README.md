
#  Apple Store Dashboard – Power BI Project

##  Project Summary

This Power BI project utilizes real-world Apple Store data sourced from Kaggle to provide a comprehensive analysis of business performance, including sales trends, product performance, warranty claims, and store-level operations. The report integrates multiple datasets to create a unified view of Apple Store activities, enabling interactive exploration and decision-making through dynamic filters and visualizations.

---

##  Project Objectives

- Analyze sales performance across Apple Stores globally  
- Identify top-selling products and categories  
- Evaluate revenue trends and sales volumes over time  
- Understand geographic distribution of sales  
- Track product warranty claims and repair outcomes  
- Build a multi-relational data model for accurate analysis

---

##  Dataset Structure

The data is divided into 5 related tables, simulating a normalized database schema:

1. ** Category Data**  
   - `category_id`, `category_name`  
   - Defines the main product categories (e.g., iPhone, Mac, Accessories)

2. ** Products Data**  
   - `product_id`, `product_name`, `category_id`, `launch_date`, `price`  
   - Links each product to its category and tracks launch date and pricing

3. ** Sales Data**  
   - `sale_id`, `sale_date`, `store_id`, `product_id`, `quantity`  
   - Transaction-level data capturing store sales over time

4. ** Stores Data**  
   - `store_id`, `store_name`, `city`, `country`  
   - Geographical mapping of store locations

5. ** Warranty Data**  
   - `claim_id`, `claim_date`, `sale_id`, `repair_status`  
   - Tracks customer claims and repair statuses post-purchase

---

##  Tools & Technologies Used

| Tool        | Purpose                                     |
|-------------|---------------------------------------------|
| **Power BI**     | Data visualization & dashboard development     |
| **Power Query**  | ETL: Data cleaning and transformation          |
| **DAX**          | Custom measures, calculated columns, KPIs      |

---

##  Dashboard Features

-  **Revenue & Quantity Analysis**  
  Total revenue and units sold by product, category, and region

-  **Time Series Breakdown**  
  Sales trends over months and years with dynamic date filters

-  **Store Performance**  
  Compare store-level sales and highlight top/bottom performers

-  **Regional Insights**  
  Map visualizations of sales by country and city

-  **Warranty Tracking**  
  View number of warranty claims by product and repair status

---

##  Dashboard Preview


![store](https://github.com/user-attachments/assets/1e935a61-8f6c-4570-ad70-ce92560c0e0b)

![sales](https://github.com/user-attachments/assets/3b75856c-3496-4028-acc7-cd1c15a9f8a3)

![warranty](https://github.com/user-attachments/assets/a591f908-ae85-4a51-a508-2ef8fb390cc0)

---

##  How to view / use this dashboard.

1. **Clone or Download** this repository  
2. Open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/)  
3. Explore the dashboard by interacting with slicers, visuals, and tooltips  
4. Refresh the dataset or connect to a live API to keep it current


*END*
