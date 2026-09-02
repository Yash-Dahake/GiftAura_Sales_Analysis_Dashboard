
# 🎁 GiftAura Sales Analysis – Excel  Project

## 📌 Executive Summary
This project provides an end-to-end exploratory data analysis and interactive dashboard solution built in **Microsoft Excel** for **GiftAura**, an e-commerce platform specializing in curated gifts for various occasions. 

By analyzing transactional customer order data, this project evaluates key revenue metrics, temporal purchasing patterns, high-performing product categories, top customer locations, and logistics performance. The resulting dashboard provides actionable insights to help business stakeholders optimize inventory planning, targeted marketing campaigns, and shipping operations.

---

## 🛠️ Tools & Technologies
* **📊 Data Analytics & Spreadsheet Software:** Microsoft Excel
* **🧹 Data Processing & ETL:** Power Query, Data Cleaning, Text Standardization, Data Formatting
* **🧮 Calculations & Formulas:** Advanced Excel Formulas (`DATEDIF`, `INT`, `TEXT`, `SUM`, `AVERAGE`, `COUNTIF`)
* **📉 Data Aggregation:** Dynamic PivotTables & PivotCharts
* **🎛️ Interactive Features:** Custom Slicers (Occasion filter, Order Date Timeline, Delivery Date Timeline)

---

## 💻 Technical Stack & Core Competencies
* **💻 Languages & Database Systems:** SQL | PostgreSQL | Python
* **📈 Analytics Tools:** Excel | Power BI
* **🎯 Domain:** Data Analytics, Data Operations, Business Intelligence

---

## 📁 Project Structure
```text
GiftAura-Sales-Analysis/
│
├── GiftAura-dataset/                # Raw dataset files and source tables
│   ├── Customers.csv / .xlsx
│   ├── Orders.csv / .xlsx
│   └── Products.csv / .xlsx
│
├── giftaura_excel_project.xlsx      # Main workbook containing raw data, calculations, PivotTables, & Dashboard
├── Dashboard_Screenshot.png         # Image preview of the interactive dashboard
└── README.md                        # Project documentation and summary
```
---

📑 Dataset Overview & Data Preparation
🔍 Dataset Overview
The dataset contains transactional records of 1,000 orders placed across major Indian cities, capturing order timestamps, delivery dates, product categories, pricing, unit quantities, and occasions.

🔄 Key Data Cleaning & Feature Engineering Steps
⏱️ Order Processing Duration: Created a calculated column to compute the exact delivery lead time in days:

Order-Delivery Time (Days)=Delivery_Date−Order_Date
📅 Temporal Extraction: Extracted specific order hours, days, and months from timestamps to perform granular time-series analysis:

Order Hour: Derived using =INT(Order_Time * 24)

Order Month: Extracted to categorize temporal trends across peak festive seasons.

✅ Data Quality Validation: Standardized text fields, reformatted currency values to INR (₹), removed duplicate records, and ensured zero missing values in primary key columns.

---

📊 Dashboard Overview & Key Performance Indicators (KPIs)
📊 Key Performance Scorecard
📦 Total Orders: 1,000

💰 Total Revenue: ₹35,20,984.00

🚚 Average Delivery Time: 5.53 Days

💳 Average Customer Spend: ₹3,520.98 per order

---

❓ Business Questions & Core Insights
1. What are the key performance metrics of GiftAura's sales operations?
GiftAura generated ₹35.21 Lakhs across 1,000 completed orders, yielding an average order value (AOV) of ₹3,520.98. The overall logistics operations average 5.53 days for complete order delivery.

2. Which festive occasions drive the highest revenue?
💍 Anniversary gifts generated the highest revenue at ~₹6.72 Lakhs, closely followed by 🪢 Raksha Bandhan (~₹6.28 Lakhs) and 🎨 Holi (~₹5.71 Lakhs).

❤️ Valentine's Day (~₹3.31 Lakhs) and 🪔 Diwali (~₹3.13 Lakhs) recorded lower revenue totals relative to expectations, pointing to potential under-stocking or uncaptured seasonal demand.

3. What are the top product categories by sales volume and value?
🎨 Colors dominated product category sales, contributing ₹3.36 Lakhs in total revenue.

🧸 Soft Toys (₹2.45 Lakhs) and 🍬 Sweets (₹2.31 Lakhs) performed strongly as complementary gift additions.

☕ Mugs and 🪴 Plants recorded the lowest revenue streams (~₹64,000 - ₹67,000), indicating lower customer preference or lower price points.

4. What are the seasonal and monthly sales trends?
Sales experience major surge peaks during February (~₹7.06 Lakhs) and August (~₹7.38 Lakhs), perfectly coinciding with Valentine's gifting and Raksha Bandhan preparation.

Significant revenue drop-offs occur during shoulder months such as April–July (averaging ~₹1.4 Lakhs – ₹1.6 Lakhs monthly).

5. At what hours of the day do customers place the most orders?
Order placement activity peaks during late evening hours between 18:00 (6 PM) and 20:00 (8 PM), exceeding ₹1.80 Lakhs per peak hour.

A secondary surge occurs around mid-day at 06:00 AM – 07:00 AM.

6. Which individual products are top revenue drivers?
The top 5 revenue-generating items in the catalog are:

🏆 Magnam Set (~₹1,21,000)

🎁 Dolores Gift (~₹1,06,000)

📦 Harum Pack (~₹1,01,000)

🛍️ Deserunt Box (~₹97,000)

✨ Quia Gift (~₹1,14,000)

7. What are the top geographic markets (cities) by order volume?
GiftAura holds a strong customer base in Tier-2 and Tier-3 urban markets:

📍 Imphal leads all regions with 29 orders, followed by 📍 Dhanbad (28 orders) and 📍 Kavali (27 orders).

Guntakal, Haridwar, and Dibrugarh also rank among the top 10 performing cities.

---

🔍 Findings and Conclusion
🎯 Key Findings
🎉 Festive Peaks Drive Bulk Sales: Over 40% of annual revenue is generated across two primary seasonal peaks in February and August.

📦 Category Polarization: A small subset of product categories (Colors, Soft Toys, Sweets) drives the majority of total transaction value.

⏰ Prime Purchasing Windows: Customer purchasing behavior is heavily concentrated in the evening hours (6:00 PM – 8:00 PM).

📍 Emerging Regional Markets: Order volume is heavily distributed across growing urban centers like Imphal, Dhanbad, and Kavali rather than strictly metropolitan hubs.

---

🚀 Strategic Business Recommendations
📈 Capitalize on Peak Seasonal Spikes: Allocate higher digital marketing budgets 2–3 weeks prior to February and August to capture early-bird festive shoppers. Increase inventory stock levels for top-selling items ahead of peak seasons.

🛍️ Revamp Underperforming Categories: Bundle lower-performing categories (such as Plants and Mugs) with high-revenue items like Colors or Sweets to boost overall basket size.

⏰ Optimize Ad Scheduling: Schedule automated promotional notifications, emails, and social media ad campaigns during peak customer activity hours (5:00 PM – 8:00 PM).

🚚 Enhance Regional Supply Chain Operations: Focus regional fulfillment logistics in high-volume regions (Imphal, Dhanbad, Kavali) to reduce the average delivery window from 5.53 days to 3–4 days.

---

👤 Author
Yash Dahake

🎓 MCA | Data Analytics Enthusiast

🛠️ Skills: SQL | PostgreSQL | Python | Excel | Power BI | Data Analytics


****
