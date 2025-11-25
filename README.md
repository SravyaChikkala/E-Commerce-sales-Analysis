📁 Project Structure
ecommerce-analytics/
│
├── data/
│   └── ecommerce_sales.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── visuals/
│   ├── revenue_by_region.png
│   ├── revenue_by_month.png
│   ├── top_products.png
│   ├── category_revenue.png
│   └── customer_type_revenue.png
│
├── dashboard/
│   └── ecommerce_analytics_dashboard.pbix
│
└── README.md

🎯 Objective

The goal of this project is to explore and analyze e-commerce sales data to identify:

High-revenue regions

Monthly revenue trends

Best-selling products

Customer type performance (New vs Returning)

Category-wise sales distribution

Payment method patterns

Actionable business insights for decision-making

🧰 Tools & Technologies Used

Python → Pandas, Matplotlib

Power BI Desktop → Interactive dashboard

Excel → Dataset creation

Google Colab / Jupyter Notebook → Code execution

🧹 Data Cleaning & Preparation (Python)

Performed in the notebook:

Converted OrderDate to datetime format

Ensured Quantity and UnitPrice were numeric

Removed invalid or missing records

Created key features:

Revenue = Quantity * UnitPrice

Month = OrderDate (YYYY-MM)

📈 Exploratory Data Analysis (Python)

Key analysis includes:

Revenue by Region

Revenue by Month

Revenue by Category

Quantity sold by Category

Top 5 Products by Revenue

Revenue by Customer Type

Payment Method distribution

Charts (PNG) are saved in the visuals/ folder.

📊 Power BI Dashboard

The interactive Power BI dashboard includes:

Revenue by Region (Bar Chart)

Revenue Trend by Month (Line Chart)

Top 5 Products by Revenue (Bar Chart)

Revenue by Category (Donut Chart)

Revenue by Customer Type (Column Chart)

Payment Method Breakdown (Pie Chart)

Filters/Slicers:

Region

Category

Customer Type

📌 Dashboard File:
dashboard/ecommerce_analytics_dashboard.pbix

🔍 Key Insights

(Some example insights — update based on your results)

The South region contributes the highest revenue.

Electronics is the top-performing category by revenue.

Returning customers spend more on average than new customers.

January shows strong sales indicating seasonality or promotions.

Credit Card and UPI are the most used payment methods.

Top products like Laptop Sleeve, Bluetooth Speaker, and Smartwatch drive a significant portion of revenue.

🧭 Business Recommendations

Increase marketing investment in high-performing regions (South & North).

Improve promotions or bundle offers for low-performing categories.

Create a loyalty program for returning customers (high-value segment).

Ensure inventory availability for the top 5 best-selling products.

Promote digital payment options to reduce checkout drop-off.
