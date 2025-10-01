
# Excel Sales Data Cleaning & Dashboard Project

Project Overview
This project demonstrates how to clean messy sales data in Excel, apply advanced formulas, and create a professional sales dashboard with KPIs.  

---

 Project Structure
- **cleaning/**  
  - `raw_data.csv` → Original messy dataset (with duplicates, missing values, text numbers, inconsistent dates, etc.)  
  - `sales.xlsx` → Cleaned dataset visualized with charts and KPIs  

- **sales.xlsx**  
  - Final cleaned data table  
  - Pivot tables for Sales, Profit, Categories, Customers  
  - Dashboard combining KPIs and charts  

---

##  Data Cleaning Steps
1. Removed duplicates (Customer Names, Order IDs).  
2. Fixed inconsistent date formats (dd/mm/yyyy vs dd-mm-yyyy).  
3. Converted text numbers (Sales, Profit) into numeric format.  
4. Used `TRIM`, `CLEAN` to remove extra spaces.  
5. Handled missing values using `IFERROR`, blank replacements.  
6. Created calculated columns for:
   - Profit Margin
   - Order Month (from Order Date)

---

##  Dashboard Features
- **KPIs**:
  - Total Sales
  - Total Profit
  - Total Orders
  - Average Order Value (AOV)
  - Profit Margin %
  - Top Customer by Sales

- **Charts**:
  - Sales by Category (Bar Chart)
  - Monthly Sales Trend (Line Chart)
  - Customer Sales Comparison (Column Chart)
  

---

-- Tools Used
- Microsoft Excel  
- Excel Formulas (VLOOKUP, IF, COUNTIFS, IFERROR, etc.)  
- Pivot Tables  
- Power Query (for duplicate removal & cleaning)  

---

## 📈 Key Learnings
- Hands-on practice in data cleaning and transformation.  
- Experience in KPI building and dashboard design.  


---

