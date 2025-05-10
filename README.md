# 📊 Sales Performance Dashboard
📝 Project Overview
This project is a Sales Performance Dashboard built using Power BI and Excel. It provides interactive insights into sales, profit, and quantity performance across different product categories, sub-categories, and regions for the year 2014. This dashboard helps stakeholders identify key trends and make informed business decisions.

🧰 Tools Used
Power BI – For creating interactive dashboards and visualizations
Microsoft Excel – For data cleaning and preparation

🧹 Data Cleaning Steps (in Excel)
Before importing the data into Power BI, the following data cleaning steps were performed in Excel:
Removed Blank Rows & Columns – Ensured no empty rows or columns existed in the raw dataset.
Handled Missing Values – Replaced missing values in numerical fields (Sales, Profit, Quantity) with 0 or used logical imputations.
Trimmed Whitespace – Cleaned product names and category fields using TRIM() and CLEAN() functions.
Standardized Formats – Ensured consistent formatting for:
Dates (converted to proper Date format)
Currency values (rounded to 2 decimal places)
Filtered Irrelevant Entries – Removed test data or outlier rows with invalid values (e.g., negative quantity unless verified).
Added Calculated Columns (if applicable) – Such as:
Year or Month columns from Order Date using TEXT() or MONTH() functions
Profit Margin = Profit / Sales

📈 Dashboard Features (Power BI)
✅ KPIs Displayed:
Total Sales: $151.78K
Total Quantity Sold: 4569 units
Total Profit: $22.59K

🗺️ Visuals & Insights:
Donut Chart: Sales contribution by Region (West, Central, East, South)
Line Chart: Monthly trend of Sales vs. Profit (shows peak in October and December)
Bar Chart: Sales by Sub-Category (e.g., Storage has highest sales)
Table View: Detailed product-wise breakdown of Sales and Profit
Category Selector: Slicer to filter by Furniture, Office Supplies, or Technology
Year Buttons: Timeline toggle to switch between different years (currently showing 2014)

