# Competitor Sales Analysis 

An interactive **Power BI** dashboard benchmarking a company's sales performance ("Sintec") against key competitors — Affinity, Aquatail, Artisans, Atlas, Diament, Ductal, Fabrean, Inventio, and Lignum — across categories, regions, and time.

## 📊 Project Overview

Understanding how a brand is performing relative to competitors is critical for pricing, product, and go-to-market decisions. This project analyzes multi-year, multi-country sales data across manufacturers, product categories, and segments to answer:

- How is total revenue trending over time, and what's driving growth or decline?
- How does the company's ("Sintec") market share compare to competitors, by country and manufacturer?
- Which product categories, segments, and individual products are the strongest and weakest performers?
- What factors most influence revenue increasing or decreasing, and which products/manufacturers matter most?

## 🛠️ What I Did

- Cleaned and modeled multi-year competitor sales data (revenue, units, price, manufacturer, category, segment, product, country, and date fields) in Power BI.
- Built DAX measures for **Total Revenue**, **PY (Prior Year) Sales**, **% Growth**, and **Market Share**.
- Designed a 2-page interactive report with consistent branding, competitor logo filters, and cross-filtering:
  - **Competitor Sales Analysis** — an executive overview page with total revenue vs. prior-year sales, market share KPI, revenue trend by month with % growth, a waterfall chart of revenue by segment and year, a stacked column chart of revenue by country and manufacturer, and a detailed matrix table of revenue by category with conditional formatting on % growth.
  - **Advanced Insights** — a deep-dive analysis page featuring a decomposition tree (Category → Segment → Product) to drill into revenue drivers, and a **Key Influencers (AI visual)** identifying which products and manufacturers most strongly increase or decrease revenue.
- Added interactive competitor logo buttons across the top of every page to filter the whole report by manufacturer with a single click.
- Used a waterfall chart to visualize year-over-year revenue movement by segment, and a decomposition tree to let users explore the revenue hierarchy top-down.
- Applied conditional (heatmap-style) formatting to the category revenue table to instantly flag high- and low-growth categories.
- Used Power BI's natural-language insight generator to auto-summarize what's driving revenue increases (e.g., manufacturer and product-level effects).

## 🔑 Key Outcomes & Insights

- **Total revenue reached $363M**, up from **$230M** in the prior year — a **57.79% growth rate** year-over-year.
- The company holds a **19.63% market share** relative to the competitor set analyzed.
- **Urban** is the dominant category, contributing **$28.0M in revenue at 77.17% of total GT revenue** with **58.66% growth**, while **Convenience** and **Extreme** segments posted the strongest growth rates (**53–65%**) within Urban.
- Revenue by country and manufacturer shows the **USA** as the largest market (**~$1.23M+ combined across manufacturers**), with **Aquatail** and **Sintec** as the leading manufacturers by volume in that market.
- The monthly revenue trend shows a **peak around May–June**, with growth (%) fluctuating between roughly **50–70%** across the year, highlighting seasonality worth planning around.
- The **Key Influencers visual** identified that revenue is most likely to increase when the **product is Lignum UC-24** (avg. +$786.8) or **Maximus UM-80** (avg. +$674.4), and that revenue increases were most strongly driven **when the manufacturer was Artisans** (+518.37 on average) — giving clear, data-backed direction for where to focus sales and marketing effort.
- The decomposition tree makes it possible to trace revenue from the **total ($36.28M in the Urban view)** down through **Category → Segment → Product** in seconds, without writing a single query.

## 🧰 Tools & Skills Used

`Power BI Desktop` · `DAX` · `Data Modeling` · `Decomposition Tree` · `Key Influencers AI Visual` · `Waterfall Charts` · `Conditional Formatting` · `Data Visualization` · `Competitive/Market Analysis`

## 📸 Screenshots

### Competitor Sales Analysis (Overview)
<img width="1446" height="791" alt="Screenshot 2026-09-02 002125" src="https://github.com/user-attachments/assets/e3a4cc21-7c1c-4301-adff-84e316dd2b79" />


### Advanced Insights (Decomposition Tree & Key Influencers)
<img width="1445" height="791" alt="Screenshot 2026-09-02 002159" src="https://github.com/user-attachments/assets/29225042-f6a3-452d-8982-8093068d5d8e" />


## 📁 Repository Contents

```
├── Competitor_Sales_Analysis_in_Power_BI.pbix   # Power BI report file
├── screenshots/                                  # Dashboard screenshots
└── README.md
```

## 🚀 How to View

1. Download `Competitor_Sales_Analysis_in_Power_BI.pbix`.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the manufacturer logo buttons and date/category slicers to explore the data interactively.
