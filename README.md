# 🌿 Plant Sales Analysis Dashboard: 2023–2025 Growth & Profitability Insights

## 1. Short Description / Purpose

The Plant Sales Analysis Dashboard is an interactive Power BI report designed to monitor and analyze the year-over-year performance of plant product sales across countries, months, and product categories. This dashboard supports decision-makers in identifying trends, underperforming regions, seasonal patterns, and growth opportunities across the plant business.

## 2. Tech Stack

This dashboard was built using the following tools and technologies:

- **Power BI Desktop** – Core visualization and analytics platform  
- **Power Query** – Used for data cleaning, shaping, and joining multiple sources  
- **DAX (Data Analysis Expressions)** – For year-to-date (YTD), prior year (PYTD), gross profit %, and dynamic visuals  
- **Data Modeling** – Establishes relationships between tables like country, product, sales, and account-level performance  
- **PBIX File** – Development and deployment format  

## 3. Data Source

**Internal Plant Sales Dataset** collected across global regions between 2023 and 2025.

Structured data includes:

- Sales transactions with time-series dimension (month & quarter)  
- Product types (Indoor, Outdoor, Landscape)  
- Account-level data  
- Metrics such as Quantity Sold, Gross Profit, Sales Revenue  
- Country-wise breakdown of sales activity  

## 4. Features / Highlights

### • Business Problem

Global sales teams and category managers lack visibility into real-time performance trends, underperforming markets, and gross profit drivers—especially when tracking results year over year by region and product type.

### • Goal of the Dashboard

To empower stakeholders with a unified analytics view to:

- Compare **Year-To-Date (YTD)** and **Prior Year-To-Date (PYTD)** sales performance  
- Identify bottom-performing countries  
- Spot seasonal spikes and product trends  
- Analyze **Gross Profit Percentage (GP%)** to evaluate profitability  
- Drill into account-level performance to detect revenue and margin outliers  

### • Walkthrough of Key Visuals

- **Key KPIs (Top Center)**  
  - YTD Quantity: **555.66K**  
  - YTD vs PYTD Growth: **+17.05K**  
  - PYTD: **538.61K**  
  - Gross Profit %: **0.40**

- **Bottom 10 Countries by YTD vs PYTD (Treemap)**  
  Highlights underperforming regions like China, France, Sweden, and Japan with specific shortfalls in quantity sold.

- **Monthly Quantity Change (Waterfall Chart)**  
  Tracks quantity sold month-by-month, showing increases and decreases relative to PYTD.

- **Monthly Sales Value by Product Type (Stacked Bar + Line)**  
  Breaks down monthly performance across product types (Indoor, Landscape, Outdoor) with PYTD overlay.

- **Account-Level Profitability Scatterplot**  
  Visualizes gross profit % vs. YTD sales value at the account level. Helps detect high-revenue/low-margin accounts for deeper investigation.

## 5. Business Impact & Insights

- 📉 **Risk Alert**: Major markets like China and France are showing significant declines in volume. These regions may need immediate sales strategy revision or promotional support.  

- 📊 **Seasonality Uncovered**: Peak performance is seen in Q2 and Q4, with July and September experiencing noticeable drops—likely linked to operational or demand-side seasonality.  

- 🔍 **Product Trends**: "Indoor" and "Outdoor" categories consistently outperform "Landscape" across the year—indicating areas for marketing focus and inventory alignment.  

- 💸 **Profitability Awareness**: The scatterplot helps flag accounts with high volume but poor margins, guiding account managers on pricing renegotiation or product mix refinement.  

## 6. Screenshots / Demos

## 6. Screenshots / Demos

![Dashboard Screenshot](https://github.com/shashireddyt8/Yearly-Sales-of-Plants/blob/main/Dashboard_Screenshot_Sales%20Analysis.png?raw=true)

