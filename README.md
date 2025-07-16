# ☕ Bright Coffee Shop Sales Analysis (BRIGHTLIGHT)

Welcome to the Bright Coffee Shop Sales Analysis project! This repository contains the full end-to-end analysis to provide actionable business insights for the new CEO of Bright Coffee Shop.

PROJECT OBJECTIVE 

The goal of this project is to extract insights from historical daily transactional data to help the CEO grow revenue and improve product performance.  

The analysis answers key questions like:
- Which products generate the most revenue?
- What time of day does the store perform best?
- What are the sales trends across products and time intervals?
- How can sales performance be improved?

---
PROJECT STRUCTURE

├── 📊 Miro_Plan/Architecture_Diagram.pdf
├── 📈 Processed_Dataset.xlsx
├── 🗃️ SQL_Scripts.sql
├── 📊 Sales_Dashboard.xlsx
├── 🎞️ CEO_Presentation.pptx
├── 📄 README.md
```
TASKS COVERED
1. Planning & Architecture (Miro)
- Data Flow & Architecture Diagram (Source → ETL → Storage → Analysis)
- Defined key insights and calculations:  
  - `Total Amount = unit_price * transaction_qty`
  - Grouping transactions by 30-minute intervals  
  - Identifying best & worst performing products

2. Data Processing (Snowflake)**  
- Converted raw Excel data to CSV  
- Loaded data into Snowflake
- Performed ETL transformations:
  - Corrected unit_price formats
  - Created time buckets
  - Calculated total_amount
  - Grouped data for meaningful analysis

---3. Data Analysis & Visualization (Excel)
- Generated dashboards and pivot tables:
  - Total revenue per product type
  - Peak sales times
  - Best-selling items
- Used charts & visuals to tell the sales story

---
4. Presentation
- Methodology document
- Presentation slides with insights and recommendations:
  - Run marketing campaigns during slow time slots
  - Stock up on best-sellers
  - Promote underperforming products
- Next Steps:
  - Automate daily sales reporting
  - Scale analysis to multiple locations
  - Implement loyalty programs

##TOOLS USED

- SQL:** Snowflake,
- Data Viz:Microsoft Excel
- Planning:Miro
- Presentation:, Canva
