# Global Superstore Command Center 🚀
**Interactive Power BI Dashboard for Sales & Profit Intelligence**

## 📊 Project Overview
This project presents a comprehensive Power BI dashboard designed for **Global Superstore**, a multinational retail company. The dashboard enables leadership teams to make **data-driven decisions** by offering insights into revenue, profitability, customer segmentation, discounting strategies, and logistics performance.

## 🎯 Business Objectives
1. **Revenue Growth**  
   Identify under-penetrated regions and high-potential product categories.

2. **Margin Improvement**  
   Analyze the impact of discounts on profitability and recommend optimal thresholds.

3. **Operational Efficiency**  
   Benchmark shipping performance across modes and regions.

4. **Customer Profiling**  
   Uncover segments delivering the highest lifetime value.

## ❓ Key Research Questions
- Which regions and sub-categories are outperforming or underperforming?
- At what discount rate does volume outweigh margin erosion?
- Is expedited shipping worth the cost in terms of customer retention and revenue?
- Which cities are seeing spikes in returns or delays?
- How do seasonal trends impact planning?

## 📂 Data Sources
- `Orders`: Transaction-level data
- `Returns`: Returned orders
- `People`: Customer segments

**Time Frame:** Jan 2016 – Dec 2019  
**Fields Used:** Order Date, Ship Date, Ship Mode, Region, Country, City, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit

## 🧠 Data Modeling
- Star schema with fact and dimension tables.
- Calculated Column: **Order Lead Time** = `Ship Date - Order Date`

## 📐 DAX Measures
- Total Sales, Total Profit, Profit Margin (%)
- Average Discount, Discount-to-Profit Correlation
- Year-over-Year Sales & Profit Growth
- Average Lead Time by Ship Mode

## 📈 Visualizations
- **Dashboard Page:** KPI cards, trendlines, regional heatmaps
- **Category Analysis:** Drill-down bar charts
- **Discount Impact:** Scatter plot (Discount % vs. Profit Margin %)
- **Logistics Analysis:** Box plot for lead time
- **Geographical View:** Profit Margin by Country/City on a map
- **Customer Segments:** Small multiples/slicer views for Consumer, Corporate, and Home Office

## ✅ Success Criteria
- Interactive and synchronized filters with full drill-through
- Dashboard loads in under 5 seconds
- Includes at least 3 actionable insights
- Accompanied by a 5-slide walkthrough deck

## 📁 Files Included
- `LOKESH_KUMHAR_CPDA_B1.pbix` – Power BI dashboard file
- `Problem_Statement_v1.pdf` – Problem definition and project scope
- `Presentation.pptx` *(to be added)* – Summary walkthrough (if available)

## 📌 Usage
To explore the dashboard:
1. Open `LOKESH_KUMHAR_CPDA_B1.pbix` in Power BI Desktop.
2. Use slicers and filters to interact with different views.
3. Navigate through tabs to explore Sales, Discounts, Logistics, Geography, and Segments.

---

## 👤 Author
**Lokesh Kumhar**  
Certified Power BI Developer | CPDA_B1 Batch

---

## 📝 License
This project is for academic and learning purposes under the [MIT License](LICENSE).
