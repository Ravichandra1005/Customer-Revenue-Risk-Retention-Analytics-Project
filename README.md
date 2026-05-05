🚀 Customer Revenue, Risk & Retention Analytics Project
📌 Project Overview

This project focuses on analyzing customer behavior, revenue trends, returns, and delivery performance using Python and Pandas.
The goal is to generate business insights and support data-driven decision-making.

📂 Data Preparation
The dataset was initially provided in Excel format with 3 sheets:
Customers
Orders
Order Items
Each sheet was converted into separate CSV files:
customers.csv
orders.csv
order_items.csv
These CSV files were then loaded into Python using Pandas.
⚙️ Data Processing
All data processing was done using Python
Datasets were merged using:
customer_id
order_id
Created important columns:
order_value
delivery_delay_days
is_repeat_customer
is_high_value_order
customer_value_segment
customer_risk_category
order_reliability_score
🧠 Analysis Approach
Used Python functions
Used lambda expressions
Used for-loop (as required)
Used Pandas for data manipulation

All business questions were solved using grouping and aggregation techniques.

❓ Business Questions & Answers
1️⃣ High Revenue vs High Returns

Some customers generate high revenue but also return products frequently.
➡️ These customers are risky and impact profit.

2️⃣ Delivery Delay by City

Cities like Mumbai and Chennai show higher delivery delays.
➡️ Indicates logistics inefficiencies.

3️⃣ Repeat Customer Value

Repeat customers have higher average order value.
➡️ They are more valuable to the business.

4️⃣ Category Risk

Clothing and Electronics generate high revenue but also high returns.
➡️ Indicates product quality or expectation issues.

5️⃣ Payment Mode Risk

UPI shows the highest number of returns and cancellations.
➡️ It carries the highest risk.

📊 Visualizations
📈 Monthly Revenue Trend (Line Chart)
📊 Customer Segmentation (Bar Chart)
📊 Return Rate by Category (Bar Chart)
🔵 Delivery Delay vs Revenue (Scatter Plot)
🔥 City vs Category Revenue (Heatmap)
🚨 Business Problems
High-value customers are returning products frequently
Certain cities have high delivery delays
Some categories have high return rates
💡 Recommendations
Improve product quality and descriptions
Optimize delivery operations in high-delay cities
Focus on reducing returns in Clothing and Electronics
🧾 Conclusion

This project demonstrates how Python, Pandas, and data visualization can be used to analyze customer behavior, identify risks, and improve business performance through data-driven insights.

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
⭐ Final Note

This is an end-to-end data analytics project covering data cleaning, transformation, analysis, and visualization.
