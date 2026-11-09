# Farmer-Market-Sales-Insights-PowerBI-2022-2025-
An interactive Power BI dashboard project analyzing farmer market sales, revenue, product categories, farmer performance, and geographical insights using 100K AI-generated dummy records (2022–2025).


🌾 Farmer Market Sales & Insights Dashboard (2022–2025)

📊 Project Overview
Farmer Market Sales & Insightsis an interactive Business Intelligence project developed using Microsoft Power BI to analyze agricultural market sales, revenue generation, product performance, farmer participation, and geographical distribution.
The project uses an AI-generated dummy dataset containing approximately **100,000 records** to simulate real-world farmer market operations from 2022 to 2025.
The dashboard transforms raw sales data into meaningful business insights through interactive visualizations, KPI cards, filters, and data-driven analysis.

🎯 Project Objectives
- Analyze overall farmer market sales and revenue performance.
- Track monthly sales and quantity trends.
- Identify top-performing products and categories.
- Evaluate farmer participation and revenue contribution.
- Compare state-wise and market-wise performance.
- Understand customer payment preferences.
- Support business decision-making through interactive dashboards.

🖥️ Dashboard Pages
The project consists of five interactive dashboard pages:

1. Executive Overview Dashboard
- Total Revenue
- Total Quantity Sold
- Distributed Farmers
- Total Markets
- Monthly Sales Trends
- State-wise Sales Analysis
- Payment Mode Distribution
- Revenue per Market

2. Sales Performance Dashboard
- Monthly Revenue Analysis
- Quantity vs Revenue Trend
- Category-wise Sales Contribution
- Revenue per Market
- Average Price Analysis

3. Product & Category Insights Dashboard
- Category-wise Revenue Analysis
- Top 5 Products by Revenue
- Perishable vs Non-Perishable Sales
- Seasonal Product Sales Analysis
- Product Performance Comparison

4. Farmer Performance Dashboard
- Category-wise Farmer Participation
- Top 5 Farmers by Revenue
- Market Type by Farmers
- State-wise Farmer Distribution
- Revenue per Farmer Analysis

5. Market & Geography Dashboard
- State-wise Revenue Analysis
- Market Type Revenue Comparison
- Payment Mode Revenue Distribution
- Individual Market Performance
- Geographical Sales Analysis

## 📈 Key Business Insights

- Total Revenue: ₹521M (Executive Overview KPI).
- Total Quantity Sold: 6.4M units (Executive Overview KPI).
- Farmer Participation: 500 distributed farmers (Executive Overview KPI).
- Total Markets: 5.
- Top Revenue Category: Vegetables, contributing ₹897M (42.98%) in the Product & Category dashboard.
- Top Performing Product: Onion, generating ₹301.38M.
- Top Performing Farmer: F0388, generating ₹5.19M.
- Highest Revenue State: Maharashtra, generating ₹831M.
- Leading Market Type: APMC, generating ₹1,250M.
- Top Performing Market: Bengaluru Market, generating ₹420M.
- Highest Seasonal Revenue: Rabi, generating ₹587.82M.

Note: KPI values vary between dashboard pages in the source report. The figures above retain the values reported on their respective pages.

🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV Dataset
- Data Cleaning & Transformation
- Data Modeling & Relationships
- Interactive Filters & Slicers
- Data Visualization

📐 DAX Measures

Some of the key DAX measures used in this project:

1. Total Sales
```dax
Total Sales = SUM(farmmarket_Dataset[Total_Sales])
```

2. Revenue Per Market
```dax
Revenue Per Market =
DIVIDE(
    [Total Sales],
    DISTINCTCOUNT(farmmarket_Dataset[Market_Name])
)
```

3. Average Revenue Per Farmer
```dax
Avg. Revenue Per Farmers =
DIVIDE(
    [Total Sales],
    DISTINCTCOUNT(farmmarket_Dataset[Farmer_ID])
)
```

🔍 Interactive Features

- Year-wise filtering
- Month-wise filtering
- Product category filtering
- State-wise filtering
- Season-based analysis
- Market and product-level filtering
- Interactive dashboard navigation
- Dynamic KPI cards and visualizations



## 🌐 Live Power BI Dashboard

Explore the interactive dashboard:

[View Farmer Market Sales & Insights Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTAxM2JmZTctM2Y3NC00NTdkLWEwYTYtYjBlMmYwNzhkMGY4IiwidCI6IjUxZmQ2M2E1LTMyM2UtNGVjNi04ODhhLWQ5NmZhMWJmNWZlMyJ9)

💡 Business Value

This project demonstrates how raw agricultural sales data can be transformed into actionable business insights.
It helps stakeholders understand revenue patterns, product demand, farmer contributions, market performance, and geographical opportunities to support better business planning and operational decisions.

⚠️ Disclaimer

The dataset used in this project is an AI-generated dummy dataset created exclusively for educational, learning, portfolio, and demonstration purposes.
It does not represent actual farmers, businesses, markets, organizations, or financial transactions. All names, values, and records are fictional.

👨‍💻 Author
Prince Kumar

MCA Graduate | Aspiring Data Analyst | Power BI Developer
Areas of Interest: Data Analytics, Business Intelligence, Data Visualization, Microsoft Excel, SQL, and Power BI.

