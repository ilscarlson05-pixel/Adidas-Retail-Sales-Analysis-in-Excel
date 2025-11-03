# Adidas-Retail-Sales-Analysis-in-Excel
 ##  Project Objective

The main goal of this project is to analyse **Adidas retail sales performance** across products, regions, and sales methods using **Microsoft Excel**.  
By leveraging PivotTables, charts, and dashboards, the project aims to uncover key insights about:
- Which products and regions perform best
- How profit margins vary across categories
- What factors most influence sales performance
- Seasonal or time-based sales trends

This project demonstrates how Excel can be used not only for simple reporting but for business intelligence and data-driven decision-making
## 📚 Dataset Used
- **Dataset Source:** [Adidas Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)
- **Number of Rows:** ~9,000  
- **Columns:** 12 (Retailer, Region, State, City, Product, Price per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method, Invoice Date)
- **Data Period:** 2020  
- **File Type:** Excel (.xlsx)

This dataset contains Adidas sales transactions including details about product type, pricing, region, and performance metrics like sales and profit.

## ❓  Key Business Questions Answered;
1.	Find which product categories bring in the most Total Sales and Profit.
2.	What is the relationship between “Units Sold” and “Operating Profit”?

3.	How do sales differ by region and state?
4.	Which Sales Method (In-store vs Online) performs better?
5.	How efficient is each sales method at generating profit?
6.	Man Vs  Woman indicators in Different Region?

Each question was analysed using a dedicated PivotTable and visualized with a chart for clarity.

⚙️ Process

### 1️⃣ Data Cleaning
- Checked for missing values and formatting issues  
- Converted “Price per Unit” and “Total Sales” columns to numeric format  
- Removed currency symbols and commas  
- Ensured consistent date formatting (DD/MM/YYYY)

### 2️⃣ Data Preparation
- Added new calculated fields:
  - **Profit per Unit** = Operating Profit / Units Sold  
  - **Month** = Extracted from Invoice Date using `=TEXT([@[Invoice Date]],"mmmm")`
- Ensured all fields were ready for PivotTables

### 3️⃣ PivotTable Analysis
Created multiple PivotTables for each question:
- Grouped by Region, Product, and Sales Method  
- Summarized total sales, profit, and margins  
- Added slicers for dynamic filtering (e.g., by Region or Sales Method)

### 4️⃣ Visualization
- Created charts for each question:
  - Column charts for product and region comparisons  
  - Line chart for monthly trends  
  - Scatter chart for correlation (Units vs Profit)  
- Combined key visuals into one **Dashboard sheet**

### 5️⃣ Dashboard Creation
- Designed a clear and clean dashboard layout in Excel  
- Included:
  - KPIs: Total Sales, Total Profit, Avg Margin  
  - Slicers for Region and Sales Method  
  - Interactive charts linked to PivotTables



