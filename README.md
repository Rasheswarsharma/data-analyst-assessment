📊 E-commerce Data Analysis & Business Insights

Data Analyst Assessment | Order Performance • Delivery • Customer Satisfaction • Revenue

A complete end-to-end data analysis project focused on turning e-commerce order data into clear, management-ready business insights.

🎯 Project Objective

This project analyzes e-commerce order data to understand:

Overall order performance

Order status distribution

Delivery efficiency and delays

Customer satisfaction

Revenue performance

The goal is to transform raw order-level data into meaningful metrics, analysis, and visualizations that can support data-driven management decisions.

🧩 Business Questions

The analysis is designed around five core business questions:

Area

Business Question

📦 Orders

How are orders distributed across different statuses?

🚚 Delivery

How efficiently are orders being delivered?

⏱️ Delays

How frequently are orders delivered later than expected?

⭐ Satisfaction

What does customer review data indicate about satisfaction?

💰 Revenue

How does payment value vary across order statuses?

🗂️ Repository Structure

data-analyst-assessment/
│
├── 📁 data/
│   └── Assessment-Test-(Data-Analyst)-v1 (2).xlsx
│
├── 📁 code/
│   └── analysis.py
│
├── 📁 analysis/
│   └── Olist_Data_Analysis_Q3.ipynb
│
├── 📁 presentation/
│   └── Management presentation
│
├── 📁 screenshots/
│   └── Dashboard screenshots
│
└── 📄 README.md

The presentation/ and screenshots/ folders are reserved for the final management presentation and dashboard evidence.

🔄 Analysis Workflow

Raw / Source Data
       ↓
Data Quality Checks
       ↓
Date & Data-Type Preparation
       ↓
Business Metric Creation
       ↓
Order-Level Aggregation
       ↓
Data Integration
       ↓
KPI & Business Analysis
       ↓
Dashboard & Management Insights
       ↓
Recommendations

🧹 Data Preparation

The data preparation process includes:

Reviewing the dataset structure

Checking data types

Checking missing values

Checking duplicate records and order IDs

Converting date fields into datetime format

Creating delivery-performance metrics

Aggregating payment information to order level

Aggregating item information to order level

Aggregating customer review information to order level

Merging the resulting order-level datasets

Creating a processed dataset for analysis and visualization

📐 Key Metrics

Delivery Days

Measures the time between order purchase and customer delivery.

Delivery Days =
Customer Delivery Date − Purchase Date

Delivery Delay Days

Measures the difference between actual customer delivery and the estimated delivery date.

Delivery Delay Days =
Customer Delivery Date − Estimated Delivery Date

Late Order Indicator

An order is flagged as late when:

Delivery Delay Days > 0

Total Payment Value

Represents the aggregated payment value associated with an order.

📊 Key Performance Indicators

The management dashboard focuses on five primary KPIs:

Total Orders

Average Delivery Days

Late Orders

Average Delivery Delay Days

Average Review Score

Supporting views include:

Orders by Status

Average Delivery Days by Order Status

Customer Review Score Distribution

Revenue by Order Status

These measures provide a concise view of operational performance, customer experience, and revenue.

🔎 Analysis Performed

1. Order Performance

Order status distribution is reviewed to understand the overall composition of order activity and identify delivered, cancelled, unavailable, and other order outcomes.

2. Delivery Performance

Delivery time is analyzed to understand operational efficiency. Delivery performance is also reviewed by order status.

3. Delivery Delays

Actual delivery dates are compared with estimated delivery dates to identify late orders and quantify delivery delays.

4. Customer Satisfaction

Customer review scores are analyzed to understand overall satisfaction.

The analysis also compares average review scores between late and on-time delivered orders.

5. Revenue Performance

Payment data is aggregated to order level and used to compare total payment value across order statuses.

📓 Python Analysis

The project includes both a Python script and a Jupyter Notebook.

code/analysis.py

The script contains the reproducible analysis workflow, including:

Data loading

Data-quality checks

Date conversion

Delivery metric creation

Payment aggregation

Item aggregation

Review aggregation

Dataset merging

Processed-data export

KPI calculations

Revenue and delivery analysis

analysis/Olist_Data_Analysis_Q3.ipynb

The notebook documents the analytical exploration, including:

Dataset structure and shape

Missing-value checks

Duplicate checks

Order-status analysis

Date validation

Delivery calculations

Delivery outlier checks

Payment, item, and review aggregation

Processed dataset creation

Business KPI analysis

Comparison of late vs. on-time customer reviews

📈 Dashboard

A management-focused dashboard was designed in Google Looker Studio.

Dashboard KPIs

KPI

Purpose

Total Orders

Measures overall order volume

Average Delivery Days

Tracks delivery efficiency

Late Orders

Monitors delivery reliability

Average Delivery Delay Days

Quantifies delivery delays

Average Review Score

Monitors customer satisfaction

Dashboard Views

Order Status Distribution

Delivery Performance by Order Status

Customer Review Score Distribution

Revenue by Order Status

The dashboard is designed for clarity, quick interpretation, and management-level decision support.

💡 Key Findings

The analysis indicates that:

The dataset contains a high volume of orders.

Delivered orders represent a major portion of overall order activity.

Average delivery time is an important indicator of operational performance.

Customer review scores indicate generally positive customer satisfaction.

Order-status and revenue analysis provide useful management-performance visibility.

Delivery performance remains an important area for continuous monitoring and improvement.

🚀 Recommendations

1. Monitor delivery performance continuously

Track average delivery days, late orders, and delivery delay days regularly to identify operational deterioration early.

2. Investigate late and unsuccessful orders

Review late, cancelled, unavailable, and other unsuccessful orders to identify operational issues and improvement opportunities.

3. Protect customer satisfaction

Reliable delivery and effective customer service should remain priorities because delivery experience can affect the customer experience.

4. Monitor order-status performance

Track order-status trends to identify cancellations and incomplete orders and reduce avoidable operational losses.

5. Use revenue insights for management decisions

Compare payment value across order statuses to understand business performance and support operational decision-making.

🛠️ Tools & Technologies

Tool

Purpose

Python

Data preparation, calculations, validation, and analysis

Pandas

Data manipulation and aggregation

Jupyter Notebook / Google Colab

Exploratory analysis and documentation

Google Sheets

Data preparation and supporting analysis

Google Looker Studio

Dashboard and visualization

GitHub

Version control and project documentation

ChatGPT was used as an analytical/documentation assistant for understanding the dataset, analytical approaches, visualization ideas, and project documentation.

📁 Project Deliverables

The final submission is organized around the following deliverables:

Data — Assessment dataset and supporting data

Code — Python analysis script

Analysis — Jupyter Notebook

Dashboard — Management-focused Looker Studio dashboard

Presentation — Management summary of findings

Screenshots — Dashboard/project evidence

README — Project overview and methodology

▶️ Reproducibility

The Python workflow expects the relevant Olist source CSV files to be available in the working directory.

The analysis uses these source datasets:

olist_orders_dataset.csv
olist_order_reviews_dataset.csv
olist_order_payments_dataset.csv
olist_order_items_dataset.csv

Run the analysis script from the directory containing the source files:

python code/analysis.py

The workflow produces:

olist_processed_data.csv

The processed dataset combines order, payment, item, and review information at order level for downstream analysis.

⚠️ Data Quality Considerations

The analysis includes checks for:

Missing values

Duplicate records

Duplicate order IDs

Missing delivery dates

Date conversion issues

Negative delivery durations

Extreme delivery-time observations

These checks help identify data-quality issues before using metrics for management reporting.

📌 Conclusion

This project demonstrates an end-to-end data analytics workflow:

Data → Preparation → Validation → Analysis → KPIs → Dashboard → Insights → Recommendations

The resulting analysis provides management with a structured view of:

Order performance

Delivery efficiency

Delivery delays

Customer satisfaction

Revenue performance

The project is designed to support practical, data-driven decisions and highlight areas for continued operational improvement.

👤 Author

Rasheswar Sharma

Project: Data Analyst Assessment
Repository: data-analyst-assessment

Note: Dashboard and external document links can be added to this README once the final Google Looker Studio dashboard, Google Sheet, and presentation URLs are available.
