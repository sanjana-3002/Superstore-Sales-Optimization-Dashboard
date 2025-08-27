# Superstore-Sales-Optimization-Dashboard
Interactive Power BI report that analyzes sales and profitability to identify winning product bundles, optimize pricing/discounts, and guide shelf/placement decisions across categories, segments, and regions.

## 🚀 Overview

- Goal: Reveal high-impact product bundles, pricing/discount levers, and placement opportunities to improve profit.
  
- Scope: Superstore orders across categories, segments, and regions with drill-downs to sub-category/product.
  
- Method: Power Query cleaning → star schema modeling → DAX measures → interactive cross-filter visuals.

## 🔢 Data

- Source: Superstore sales dataset (orders, products, customers, regions).
  
- Unit: Order-level transactions, aggregated to category/segment/region as needed.
  
- Notes: Normalize categories, create a Date table, handle missing/duplicates, ensure consistent data types.

## 🧪 Method & Model

- Aggregation: orders → category/segment/region/product summaries.
  
- Data model: fact Orders with dimension tables (Date, Product, Customer, Region).
  
- Measures (DAX): Sales, Profit, Profit Margin, Avg Discount, Qty, YoY/MTD.
  
- Analysis: co-purchase patterns for product combos; discount vs. profit impact; segment and regional contribution.


## 📈 Results

Highlights top product pairs for cross-sell, identifies discount ranges eroding margin, and surfaces underperforming categories/regions to target.

## ✅ Dashboard Usage

- Merchandising: bundle frequent co-purchases in promos.
  
- Pricing: tune discounts to protect margin.
  
- Placement: prioritize shelf/landing spots for high-lift combos.
  
- Monitoring: track KPIs and filter by date/region/segment to guide actions.

## ⚠️ Limitations

- Based on sample retail data; results are illustrative.
  
- Combos indicate correlation, not causation.
  
- Not connected to real-time systems; refresh cadence depends on data pipeline.
