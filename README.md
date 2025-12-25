📌 Project Overview

This project demonstrates customer behavior analysis and segmentation using the RFM (Recency, Frequency, Monetary) framework in Power BI.

The main objective is to identify high-value, at-risk, and potential customers, enabling data-driven strategies for retention, conversion, and revenue growth.

The analysis is based on the Adventure Works sample dataset, commonly used for business intelligence and analytics case studies


🎯 Business Objectives

Segment customers based on purchasing behavior

Identify high-value customers for targeted marketing

Detect at-risk customers and design retention strategies

Convert first-time or low-frequency buyers into loyal customers

Analyze revenue trends across regions and products


📂 Dataset

Source: Adventure Works sample dataset

Domain: Retail / E-commerce (Bicycles & Accessories)

Format: CSV

Tables:

Fact Table: SalesOrderDetail

Dimension Tables: Customers, Products, Dates, Geography

The dataset was modeled using a Star Schema for performance and analytical clarity.

In addition to Power BI, the RFM metrics and customer segmentation were also implemented entirely in SQL.
This demonstrates the ability to perform advanced customer analytics directly at the database level, which is critical for real-world production environments.

The SQL implementation was used to:

Aggregate transactional data at the customer level

Calculate Recency, Frequency, and Monetary metrics

Assign RFM scores (1–5) using quantile-based logic

Classify customers into strategic segments


🧠 Analytical Approach
RFM Scoring

Each customer is scored on:

Metric	Description	Scale
Recency (R)	How recently the customer purchased	1–5
Frequency (F)	How often the customer purchased	1–5
Monetary (M)	Total spending by the customer	1–5

RFM scores were calculated at the customer level, not at the product level.
Products were used as inputs to measure customer behavior.

Customer Segments

Based on RFM scores, customers were categorized:

Segment	Description
Top Value	High R, F, M – high revenue & frequent buyers
Need Retention	High past value but declining engagement
Need Conversion	New or low-frequency customers with growth potential
No Action	Low value, infrequent buyers



📊 Key Metrics

Total Revenue: $20.06M

Total Customers: 19.12K

Average Order Value (AOV): $1.71K

Repeat Purchase Rate: 10%

Year-over-Year (YoY) Growth: Calculated using DAX measures

Recency, Frequency, Monetary distributions

These KPIs provide business insights on revenue concentration, customer engagement, and purchase patterns.



🌍 Geographic & Product Analysis

Top Regions: Australia & United Kingdom show strong growth

Declining Regions: Canada & Central regions

High-Revenue Products: Touring Bikes, Road Bikes

Growth Potential Products: Accessories, Helmets

Power BI Implementation

Data Modeling: Star Schema

DAX Measures:

RFM scoring

Total Revenue, AOV, Repeat Purchase Rate

YoY growth calculation

Visualizations:

KPI cards

Recency/Frequency/Monetary distribution charts

Customer segmentation matrix

Geographic & product performance charts

Interactivity: Filters, slicers, drill-through pages for detailed customer analysis



📊 Visualizations

Dashboard Overview: RFM pictures/dashboard_overview

Customer Segmentation Matrix: RFM picture/segmentation

Top Products & Revenue: RFM picture/tops 

RFM picture/need_retention

RFM picture/need_conversation




🎯 Business Recommendations

Top Value: Loyalty programs, VIP offers, high-value product bundles

Need Retention: Reactivation campaigns, geo-specific promotions, personalized discounts

Need Conversion: Post-purchase incentives, product bundling, targeted campaigns

No Action: Minimal focus; consider long-term nurturing strategies



👤 Author

Directed by Diyorbek
Data Analyst | Power BI | Customer Analytics

Next Steps

Extend dashboard with customer drill-through pages

Implement predictive analytics for churn

Add dynamic segmentation based on time-period

