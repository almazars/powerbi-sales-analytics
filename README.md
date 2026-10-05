# powerbi-sales-analytics
 E-commerce Store Sales Analysis Project
# Electronics Retail Sales & Profitability Analytics Dashboard

An interactive, multi-page business intelligence dashboard developed in **Power BI** to analyze multi-channel retail operations across sales performance, customer demographics, inventory turnover, margin distribution, and scenario forecasting.

---

## 📌 Project Overview

This dashboard serves as a comprehensive analytical toolkit designed to monitor revenue streams, pinpoint low-margin products, track operational target fulfillment across regional retail stores, and simulate forward-looking financial scenarios using What-If parameters.

### Key Focus Areas:
- **Product & Assortment Performance:** Categorical sales split, low-margin segment diagnostics, and category-level hierarchy breakdowns.
- **Store & Regional Dynamics:** Geographic distribution across cities, square-meter efficiency, and store-level sales volumes.
- **Customer Segmentation:** Demographic distribution (gender, age cohorts, profession) and customer acquisition channels.
- **Supply Chain & Logistics:** Multi-year shipment volume trends, weight-class distribution, and carrier capacity trends.
- **Target vs. Actual Analysis:** Evaluation of OPEX targets, sales execution rates, and yearly revenue composition.
- **Profitability & Margins:** Decomposition of margins across brands, price points, and Cost of Goods Sold (COGS).
- **Forecasting & What-If Modeling:** Parametric multipliers to project future revenue and profitability variations.
- **Inventory Balance:** Cumulative purchase and sales reconciliation with ending stock indicators.

---

## 🛠 Tech Stack & Tools

- **Business Intelligence Platform:** Power BI Desktop / Service
- **Data Modeling:** Star Schema architecture (Fact and Dimension relationships)
- **Calculations & Logic:** DAX (Data Analysis Expressions) for dynamic KPIs, YTD/YoY comparisons, cumulative metrics, and What-If scenario simulations
- **Data Transformation:** Power Query (ETL processes, data shaping, type casting)
- **Version Control:** Git & GitHub

---

## 📊 Dashboard Architecture & Pages

The dashboard is structured into distinct, modular report views connected via a centralized navigation panel:

1. **Navigation Page:** Central hub providing one-click access across all thematic reports.
2. **Product & Assortment (`Products`):**
   - Revenue distribution across categories (Mobile Devices, Computers, Accessories, Audio, Components).
   - Pareto analysis for lowest margin product groups.
   - Interactive Decomposition Tree breaking down sales by Brand $\rightarrow$ Category $\rightarrow$ Product.
3. **Store Performance (`Stores`):**
   - Store footprint matrix evaluating floor area, retail size, gross sales, margins, units sold, and Average Order Value (AOV).
   - Geographic sales mapping across regional retail centers.
4. **Customer Insights (`Customers`):**
   - Demographic distribution by Gender and Age cohorts (Young, Mature, Old).
   - Sales breakdown by Profession (Office, Engineer, Student, Self-Employed, Unemployed).
   - Customer acquisition channel share (Internet, Friends, Radio, Advertisement).
5. **Shipment Performance (`Shipments`):**
   - Historical shipping volumes and percentage distribution (2017–2024).
   - Logistics distribution by weight categories (Light, Moderate, Heavy).
6. **Sales Trends (`Sales Trends`):**
   - Monthly and annual revenue trajectories.
   - Year-over-Year (YoY) performance and quick date range presets (Last 1, 2, 3 Years).
7. **Target vs. Actual (`Target/Actual`):**
   - Target achievement tracking across major retail chains (Walmart, Costco, K-Mart, Best Buy).
   - Plan variance indicators and annual cost-revenue-price breakdown.
8. **Product Margin Analysis (`Margins`):**
   - Gross profit and margin rate distribution across top brands (Dell, Huawei, Samsung, HP).
   - Scatter plot correlating Cost of Goods Sold (COGS) with realized gross margin by SKU.
9. **Sales Forecast & What-If Analysis (`Forecasts`):**
   - Interactive parameter sliders for Sales Multiplier and Cost Multiplier.
   - Dynamic projection of expected sales, costs, and net margins alongside cumulative run-rate trendlines.
10. **Inventory Balances (`Inventory`):**
    - Reconciliation between cumulative purchases and unit sales.
    - Category and brand inventory concentration breakdown.

---

## 🔍 Key Business Insights

- **Target Fulfillment:** Walmart demonstrated the highest OPEX plan fulfillment rate at **99.53%**, whereas Costco recorded the lowest target achievement at **93.67%**.
- **Execution Trajectory:** Overall target fulfillment showed upward momentum between 2017 and 2019, expanding from **107.6%** to **127.7%**.
- **Product Profitability:** Among Top-20 SKUs, **Dell Phone Type 12** achieved the highest margin ($0.21B), while **Samsung Phone Type 9** occupied the lower boundary in the Bottom-20 segment.
- **Regional Sales Anchor:** The Mobile Devices segment remains the dominant revenue driver, anchored primarily by the Costco outlet in **Taraz** ($2,521M margin).

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone [https://github.com/almazars/powerbi-sales-analytics.git](https://github.com/almazars/powerbi-sales-analytics.git)

   