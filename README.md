# Spirits Distribution Intelligence  
**A plug‑and‑play MIS & BI system for multi‑outlet distribution businesses**

![Home Page](assets/Spirit_Distribution/Spirit_preview.png)

## 📌 About This Project

This is a **capstone / proof‑of‑work** project, built entirely from scratch to demonstrate how a modern MIS system solves real‑world distribution challenges.  
All data used is **synthetic** and programmatically generated; no real company or confidential data is included.  
The dashboard is designed to be **immediately adaptable** to any distribution business – liquor, FMCG, electronics, or otherwise.

> ⚠️ **Important:** The `.pbix` source file, database, and data‑generation scripts are **not** shared publicly. This repository serves as a **business‑case showcase** only. Every element represents original work created for demonstration and skills verification.

---

## 🧩 The Business Problem

Multi‑outlet distribution companies often fly blind:

- Data scattered across countless Excel files, no single source of truth.
- Daily reports take hours to compile – by the time they reach management, they're already outdated.
- No way to see which outlet is truly profitable, which brands are silently eating margins, or which products are about to go out of stock.
- Decisions are taken on gut feel, not facts.

---

## 💡 The Solution

I built a **Business Cockpit** – a complete MIS reporting system that gives leadership:

- **One screen** showing today’s revenue, profit, and red flags – before the first coffee.
- **Automatic, scheduled refresh** – no more manual copy‑paste.
- **Five interconnected dashboard pages** that answer the critical questions every morning.

---

## 📊 Dashboard Walkthrough

### 1. Executive Daily MIS  
*A single‑glance snapshot for the morning meeting*

![Daily MIS](assets/Spirit_Distribution/Daily_MIS.png)

- MTD Revenue, MTD Profit, Margin %, Units Sold, Avg Discount, Low Stock Alerts
- Daily revenue & profit trend, category contribution, top‑5 brands
- Smart Narrative auto‑generates a text summary

### 2. Brand & Category Analysis  
*Find your money‑makers and silent profit killers*

![Brand Analysis](assets/Spirit_Distribution/Brand_Analysis.png)

- Net profit by brand, volume vs. profitability scatter
- Discount impact and margin comparison against 12% target
- Brand scorecard with conditional formatting

### 3. Outlet Intelligence  
*Know exactly where to focus your sales team*

![Outlet Intelligence](assets/Spirit_Distribution/Outlet_Intelligence.png)

- Revenue geography map, outlet scorecard, heatmap
- Retail vs. bar performance comparison
- Dynamic “Top Outlet” card that updates with slicers

### 4. Inventory Alerts  
*Prevent stock‑outs before they happen*

![Inventory Alerts](assets/Spirit_Distribution/Inventory_Alerts.png)

- Stock health gauge, per‑product status table
- Reorder suggestions with quantities and value
- ABC Pareto analysis of inventory capital

### 5. Sales Trends  
*Uncover hidden patterns and seasonality*

![Trends](assets/Spirit_Distribution/Trends.png)

- 7‑day moving average, day‑of‑week heatmap
- Cumulative revenue, category mix over time
- Month‑over‑month profit change by brand

---

## 🧠 Data Model (Star Schema)

Behind the visuals lies a **proper star schema** – the gold standard for fast, accurate, and scalable business intelligence.

![Star Schema](assets/Spirit_Distribution/Star_Schema.png)

- **Fact table:** `Sales_Transactions`
- **Dimension tables:** `Product_Master`, `Outlet_Master`, `Date`, `Inventory_Report`
- **25+ DAX measures** for revenue, cost, profit, time‑intelligence, inventory valuation, and dynamic KPIs.

---

## 🔍 Key Business Insights Uncovered

From just 4 months of synthetic (but realistic) data, the dashboard surfaced:

| Insight | Business Action |
|---------|-----------------|
| 💰 Retail outlets generated **55% higher net profit** than bars | Shift promotions & sales visits to retail |
| 📉 **4 high‑revenue brands** had near‑zero margin | Flag for pricing review or delisting |
| 🏷️ Discounts above **8% correlated with a 30% margin drop** | Implement a discount cap |
| 🚨 **4 products at critical low stock** – ₹1.2L urgent reorder value | Immediate purchase order placed |
| 📅 Monday–Thursday sales **40% lower** than weekends | Target mid‑week promotions |

---

## 🛠️ Tools & Technologies

- **Data storage & querying:** SQL Server (T‑SQL, Views)
- **Data modeling:** Star schema, 25+ DAX measures
- **Visualization:** Power BI Desktop (interactive dashboards, Power Query, page navigation)
- **Data generation:** Python (Pandas, NumPy) – synthetic dataset simulating real distribution patterns

---

## 📁 Repository Contents
