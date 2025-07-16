# 📊 Power BI Cash Flow & Latvian Company Insights Dashboard

This interactive Power BI dashboard presents a **comprehensive analysis of Latvian-registered companies**, combining financial performance, regional activity, and macroeconomic trends.  

It is designed for **public institutions, investors, analysts, and planners** seeking data-driven insights into business behavior and trends across Latvia.

---

<h3 align="center">📍 Dashboard Preview</h3>

The dashboard includes multiple analytical pages with rich filtering capabilities:

- 📈 **Registration & Churn Trends**: See how companies evolve over time  
- 🏙️ **City & Industry Breakdown**: Discover where and how companies operate  
- 💶 **Financial Health**: Analyze revenue, profit, liquidity, and assets  
- 🌍 **Macroeconomic Context**: Compare company performance with GDP trends  
- 🎯 **Dynamic Filters**: Year, industry, company type, and more

<p align="center">
  <img src="https://github.com/user-attachments/assets/1a016f1f-9d1d-4a9f-8a5b-2b44bb982722" width="800" />
  <br/><br/>
  <img src="https://github.com/user-attachments/assets/89271cfd-f57d-49e1-abd3-df0afb6105a2" width="800" />
  <br/><br/>
  <img src="https://github.com/user-attachments/assets/b1e7a3cb-ac25-49f6-9735-3acdef0389f3" width="800" />
</p>

---

## 📂 Data Sources & Quality Overview

| Data Source | Description | Quality Notes |
|-------------|-------------|---------------|
| **Company Registry** | Legal address, type (SIA, IK, BDR), registration dates | ✅ Mostly complete, minor gaps in address fields |
| **Annual Reports** | Revenue, profit, assets, equity, etc. | ✅ Cleaned for nulls and extreme outliers |
| **City Metadata** | Region, location info for mapping | ✅ Verified against national registry |
| **Financial Combined Table** | Unified table from balance, P&L, cash flow | ✅ Aggregated & transformed for analysis |
| **GDP Index** | Sector-based GDP index (1995–2023) | ✅ Used for economic context |
| **Churn Table** | Metrics on company creation vs. deletion | ✅ Pulled from BigQuery, calculated churn rate |

---

## 👥 Target Users & Applications

- 🏛 **Government & Policy Makers**  
  Plan incentives based on regional trends or struggling industries.

- 📉 **Financial Analysts**  
  Assess liquidity, profitability, and company size metrics across sectors.

- 💼 **Investors & BizDev**  
  Identify growth sectors or high-performing companies for partnerships.

- 🗺 **Regional Planners**  
  Compare business density, financial health, and churn across Latvia’s regions.

---

## 🚀 Opportunities for Further Development

- 📊 Add **labor market** insights (employment, average wage)  
- 🌍 Integrate **exports/imports** data for international context  
- 🔮 Include **forecasting** models for GDP or registration trends  
- 🧭 Analyze **market concentration** by industry  
- ⚙️ Enable **company lookup** by registration number or name

---

## 📥 How to Access the Dashboard

> Due to Power BI file size limits on GitHub, the report is hosted on Google Drive:

👉 **[Download the Dashboard](https://drive.google.com/file/d/1SiYxlUNPUkb-xQsB3eKxcpXcQ4jH5d_Z/view?usp=drive_link)** (ZIP with `.pbix` file inside)

---

## ✅ Final Thoughts

This Power BI solution delivers a **data-rich, visually intuitive overview** of Latvian companies. It blends business performance metrics with macroeconomic signals — providing **a valuable tool for stakeholders seeking insight, strategy, or investment decisions.**


## ✅ Conclusion

This dashboard provides a multi-angle view of Latvian companies — combining registration, financial, and regional data. It is flexible, extensible, and highly valuable for business intelligence and public decision-making.
