# Click‑stream E‑commerce Conversion Funnel Analysis

##  Project Overview

This project analyzes **user click‑stream behavior** in an e‑commerce platform to understand the **customer journey**, **conversion funnel**, **drop‑offs**, and **time taken between funnel steps**. The dashboard is built using **Microsoft Power BI** and is designed for business and product teams to quickly identify bottlenecks and optimization opportunities.

---

##  Objectives

* Analyze customer movement across funnel stages:
  **Page View → Add to Cart → Checkout → Purchase**
* Measure **conversion rates** and **drop‑off percentages** at each step
* Calculate **average time taken between funnel stages**
* Compare performance across **traffic sources**, **regions**, **years**, and **devices**
* Provide actionable insights to improve conversions and reduce friction

---

##  Dataset Description

The analysis is based on click‑stream event‑level data with key fields such as:

* `session_id`
* `event_type` (page_view, add_to_cart, checkout, purchase)
* `timestamp`
* `traffic_source`
* `device_type`
* `country`

Each session represents a unique user journey through the platform.

---

##  Key KPIs & Metrics

### Funnel Metrics

* Total Page Views
* Add‑to‑Cart Count
* Checkout Count
* Purchase Count
* Conversion Rate (%)
* Drop‑off Rate between steps

### Time‑based Metrics

* Avg Time: **Page View → Add to Cart**
* Avg Time: **Add to Cart → Checkout**
* Avg Time: **Checkout → Purchase**
* Avg Time: **Page View → Purchase**

All time metrics are displayed in **mm:ss format** for business readability.

---

##  Dashboard Visuals

 1️⃣ KPI Cards

* Sales, Profit, Conversion Rate
* Year‑over‑Year comparison indicators

 2️⃣ Customer Journey Drop‑off Funnel

* Visualizes user drop‑off at each funnel stage
* Shows conversion percentage from the previous step

 3️⃣ Funnel Volume by Stage & Traffic Source

* Stacked bar chart showing traffic contribution by source

 4️⃣ Channel Conversion Rate Trend

* Year‑wise conversion trend by traffic source

5️⃣ Checkout Initiation Rate by Country

* Map visual highlighting geographic performance

 6️⃣ Funnel Drop‑off & Average Time Between Steps

* **Combined clustered column + line chart**
* Bars represent funnel volume
* Line represents average time taken between steps

---

##  Business Insights

* Significant drop‑off observed between **Add to Cart → Checkout**
* Mobile users contribute the highest traffic but lower conversion
* Certain countries show higher checkout initiation but lower purchase completion
* Longer average time between steps often correlates with higher drop‑off

---

## Tools & Technologies

* Microsoft Power BI
* DAX (for time calculations & funnel logic)
* Power Query (data transformation)

---

## How to Use

1. Open the `.pbix` file in **Power BI Desktop**
2. Refresh data if required
3. Use slicers (Year, Source, Region) to interact with the dashboard
4. Review funnel drop‑off and time metrics for insights

---

## Use Case

This dashboard can be used by:

* Product Managers
* Growth & Marketing Teams
* Business Analysts
* UX Optimization Teams

To identify friction points and improve overall conversion performance.

 Project Status

✅ Completed



Author: Divakar Murali
