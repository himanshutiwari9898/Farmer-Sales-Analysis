# Farmers Market Analysis Dashboard

## Project Overview
This project presents an interactive **Power BI dashboard** built to analyze
sales and quantity performance in a Farmers Market environment.  
The dashboard focuses on understanding **vendor performance, customer behavior,
product demand, and geographic trends** using relational datasets.

The goal is to convert raw transactional data into **actionable business insights**
that can support decision-making for vendors and market organizers.

---

## Dataset Description
The analysis is based on multiple CSV files representing a normalized data model:
- Customers and their purchases
- Vendors and booth assignments
- Products and product categories
- Vendor inventory
- Market dates and time attributes

All datasets used in this project are available in the `Dataset/` folder.

---

## Tools & Technologies
- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX** for calculated measures and KPIs

---

## Key Metrics Tracked
- Total Sales
- Total Quantity Sold
- Unique Customers
- Total Customers
- Total Vendors
- Total Booths

These KPIs provide a high-level snapshot of overall market performance.

---

## Dashboard Analysis Summary

### Sales Performance
- Total sales of approximately **8.67K** are generated from a small active
  customer base, indicating revenue concentration.
- Sales are dominated by a limited number of products, showing clear
  customer preference patterns.

### Vendor Insights
- Vendor performance is highly concentrated, with sales driven primarily
  by a single vendor under the current selection.
- Vendor impact on total revenue is significant due to the small number
  of participating vendors.

### Customer Behavior
- Sales are unevenly distributed across customers, with a few high-value
  customers contributing a large share of revenue.
- This highlights the importance of repeat and high-spending customers.

### Product & Quantity Trends
- Quantity sold varies significantly by product.
- High quantity sold does not always correspond to highest sales value,
  indicating price differences across products.
- Inventory planning should prioritize products with strong demand patterns.

### Geographic (Zip Code) Trends
- Sales and quantity are concentrated in specific customer zip codes.
- This suggests localized demand and potential opportunities for targeted
  marketing or booth placement strategies.

---

## Repository Structure
Farmer-Market-Analysis/
├── RawData/ # Original raw CSV files
├── Datasets/ # Cleaned / processed datasets
├── POWERBI/ # Power BI (.pbix) file
├── DashBoardScreenshot/ # Dashboard screenshots
├── Analysis/ # Business insights and analysis
└── README.md
