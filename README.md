# Data Visualization and Storytelling — Superstore Sales Dashboard
 
## Overview
 
This project is part of the DataX Labs Data Analyst Internship (Task 2). The goal was to build a Power BI dashboard on the **Superstore sales dataset** that goes beyond raw charts and tells a clear business story — highlighting what's working, what's losing money, and where the risk is concentrated. The dashboard uses KPI cards, category and sub-category comparisons, a discount-vs-profit analysis, and geographic maps, brought together in a final Executive Summary / storyboard page.
 
## Dataset
 
- **Source:** Superstore.csv (sample US retail sales dataset)
- **Fields used:** Sales, Profit, Discount, Order ID, Sub-Category, Category, State, Order Date
## Tool
 
- Power BI Desktop
## Dashboard Pages / Charts Built
 
1. **KPI Cards** — Total Sales, Total Profit, Profit Margin %, Total Order Count
2. **Sales vs Profit by Sub-Category** — horizontal bar comparison across all 17 sub-categories
3. **Discount vs Profit Scatter** — profit plotted against discount % by sub-category, to identify the point where discounting stops being profitable
4. **Sales by State (bubble map)** and **Profit by State (filled map, red = loss-making)**
5. **Sales & Profit Trend by Year/Quarter** — time series from 2014–2017
6. **Executive Summary / Storyboard page** — KPI recap, hero + supporting chart, and a written key-takeaways section
## Key Insights
 
- **Overall performance:** The business generated **$2.30M in sales** with **$286.40K in profit**, a **12.5% profit margin**, across **5,009 orders**.
- **What's working:** Categories such as **Phones, Chairs, Copiers, and Accessories** show strong, healthy profit relative to sales — these are the core profit drivers.
- **Where money is being lost:** Several sub-categories (notably **Tables** and **Bookcases**) generate meaningful sales but contribute little or negative profit, dragging down overall margin.
- **Discounting hurts margin:** The discount-vs-profit scatter shows profit swinging sharply negative for several sub-categories as discount percentage increases — heavy discounting is directly eating into profitability rather than driving profitable volume.
- **Geographic risk:** The state-level profit map shows **Texas** as the biggest loss-making state by a wide margin, with **Ohio, Illinois, and Pennsylvania** also running in the red — despite reasonable sales volume in these regions. **California and New York**, by contrast, are strongly profitable.
- **Recommendation:** Reassess discount policy on low-margin sub-categories (Tables, Bookcases) and review pricing/cost drivers in Texas and Ohio specifically, since high sales volume there is not translating into profit.
## Files in this Repository
 
| File | Description |
|---|---|
| `Superstore_Dashboard.pbix` | Power BI source file with all pages/visuals |
| `Superstore_Dashboard.pdf` | Exported visual report (all dashboard pages) |
| `Superstore.csv` | Dataset used |
| `README.md` | This file |
 
## What I Learned
 
- How to choose the right chart type for different kinds of comparisons (categorical bars vs scatter vs geographic maps)
- How to build a discount-vs-profit analysis to surface a non-obvious business insight
- How to design a summary/storyboard page that leads with conclusions instead of just repeating charts
- Best practices for dashboard layout: consistent color meaning, minimal clutter, and precise visual positioning (X/Y/Width/Height) in Power BI