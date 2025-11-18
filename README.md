# Supermarket-Sales-Dashboard
🛒 Supermarket Sales Analytics Dashboard

A Power BI dashboard that provides actionable insights into supermarket sales, profit trends, customer segments, and regional performance.

📊 Project Overview

This project analyzes supermarket sales data using an interactive Power BI dashboard.
It helps understand:

Sales trends across months

Profit performance

Customer purchasing behavior

Sales by category, sub-category, region, and segment

Popular shipping modes

Payment preferences

The dashboard is designed with clear KPIs, slicers, and clean visuals to support business decision-making.

🛠 Tech Stack

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

CSV / Excel Dataset

✨ Key Features
✔ KPIs

Total Orders

Total Sales

Total Profit

Shipment Days

✔ Interactive Visuals

Sales by Region

Sales by Payment Mode

Sales by Segment

Sales by Ship Mode

Sales by Category

Sales by Sub-Category

Profit & Sales by State (Map)

Monthly Sales Trend (Line Chart)

Monthly Profit Trend (Line Chart)

✔ Slicers

Region

Category

Segment

Ship Mode

📈 Insights Generated

West Region recorded the highest sales (33%).

Phones and Chairs are top-performing sub-categories.

COD payments are used most frequently (~43%).

Sales and profit rise significantly during October–December (Q4).

Standard class shipping is the most preferred mode.

🧮 DAX Measures Used
Total Sales = SUM('dataset'[Sales])

Total Orders = DISTINCTCOUNT('dataset'[OrderID])

Total Profit = SUM('dataset'[Profit])

Average Ship Days = AVERAGE('dataset'[Ship_Days])

Total Quantity = SUM('dataset'[Quantity])


(Note: Replace 'dataset' with your actual table name in Power BI.)

🧹 Data Cleaning (Power Query)

Steps performed:

Converted date columns to proper Date format

Ensured numeric types for Quantity, Sales, Profit

Removed nulls/duplicates

Filtered invalid values

Renamed columns for consistency

Ensured proper category labeling

🚀 How to Use

Clone or download this repository

Open Supermarket_Sales.pbix in Power BI Desktop

Explore the dashboard using slicers & filters

Replace dataset if you want to re-use template for other businesses

👩‍💻 Author

Mrudula Kagitala

GitHub: https://github.com/Mrudula-Kagitala

LinkedIn: https://www.linkedin.com/in/mrudula-kagitala
