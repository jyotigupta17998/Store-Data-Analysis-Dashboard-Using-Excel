# Vrinda Store — Annual Sales Analysis Report (2024)

**Author:** Jyoti Gupta  
**Date:** 2025-12-11  
**Tools:** Microsoft Excel (Power Query, Pivot Tables, Pivot Charts, Slicers)

---

## Executive summary (1-line)
This analysis of **25,000+** Vrinda Store transactions for **2024** identifies that **women (≈64%)** and the **30–49 age group (≈50%)** are the primary revenue drivers, and that **Amazon / Flipkart / Myntra** contribute the majority of orders — actionable insights and recommendations are provided for targeted 2025 growth.

---

## 1. Project objective
Analyze Vrinda Store’s 2024 sales to:
- Understand customer segments (gender, age),
- Identify top-performing states and channels,
- Surface category-level performance,
- Recommend high-impact actions to grow sales in 2025.

---

## 2. Files & Dataset

- **Raw dataset:**  
  https://github.com/jyotigupta17998/Store-Data-Analysis-Dashboard-Using-Excel/blob/main/data/raw/Vrinda_Store_Raw_Data.xlsx

- **Cleaned / Dashboard Workbook:**  
  https://github.com/jyotigupta17998/Store-Data-Analysis-Dashboard-Using-Excel/blob/main/dashboard/Vrinda%20Store%20Data%20Analysis.xlsx

- **Dashboard Preview Image:**  
  https://github.com/jyotigupta17998/Store-Data-Analysis-Dashboard-Using-Excel/blob/main/dashboard/Dashboard_Screenshot.png


**Dataset size:** ~**25,000** transactions  
**Primary fields:** Order Date, Order ID, Amount, Gender, Age/Age Group, State, Channel, Category, Order Status

---

## 3. Key business questions
- Monthly trend of **Sales vs Orders**  
- Which month generated the highest revenue  
- Gender and age-group purchase behaviour  
- Top 10 revenue states  
- Channel and category performance  
- Order fulfillment rate (% delivered)

---

## 4. Methodology
1. **Data cleaning:** Power Query — standardized names, corrected date formats, removed duplicates, filled/flagged missing values.  
2. **Feature engineering:** created `Month`, `Year`, and `AgeGroup` fields.  
3. **Analysis:** Pivot tables and pivot charts to compute KPIs; window/aggregate logic implemented via calculated fields.  
4. **Dashboard:** assembled interactive dashboard with slicers (Channel, Category, Gender) and timeline filters for month-level drill-down.

---

## 5. Key findings (summary)
- **Gender:** Women account for **≈64%** of total purchases.  
- **Age:** Customers **30–49 years** contribute **≈50%** of orders.  
- **Top states by revenue:** **Maharashtra**, **Karnataka**, **Uttar Pradesh** (clear concentration in these markets).  
- **Top channels:** **Amazon (≈35%)**, **Flipkart (≈22%)**, **Myntra (≈23%)** — these three channels drive most volume.  
- **Order fulfillment:** **>90%** of orders delivered successfully.  
> _Detailed KPI tables and charts are available in the dashboard workbook._

---

## 6. Recommendations (practical, prioritized)
1. **Targeted acquisition:** Run campaigns targeting **women aged 30–49** in Maharashtra, Karnataka, and Uttar Pradesh (higher CPA tolerance for high LTV segments).  
2. **Channel optimization:** Prioritize promotional partnerships and sponsored placements on **Amazon, Flipkart, and Myntra**.  
3. **Category promotions:** Bundle and cross-sell best-selling categories to increase AOV.  
4. **Operational focus:** Investigate returns/cancellations by category/channel and reduce friction to lower costs.  
5. **Measure & iterate:** A/B test targeted creatives for the top demographic and measure conversion lift month over month.

---

## 7. How to reproduce / open
1. Download the dashboard workbook: `dashboard/Vrinda_Store_Analysis_Dashboard.xlsx`  
2. Open in Excel desktop (enable editing).  
3. Use the timeline and slicers to filter by month, channel, and category.  
4. Raw data is available at `data/raw/Vrinda_Store_Raw_Data.xlsx` for verification or reprocessing.

---

## 8. Limitations / assumptions
- Dataset is limited to 2024 transactions; external market seasonality is not modeled.  
- Channel attribution is based on recorded `Channel` field — cross-channel attribution not attempted.  
- Monetary figures are analyzed as recorded (no currency conversions).

---

## 9. Next steps (optional)
- Reproduce analysis in Python / Power BI for automation and scheduled reporting.  
- Add a simple A/B testing framework for marketing campaigns to measure uplift.  
- Build a lightweight ETL (Power Query macros or Python script) to refresh the dashboard monthly.

---

**End of report**
