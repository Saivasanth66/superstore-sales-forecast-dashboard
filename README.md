# 🛒 Super Store Sales Dashboard — Power BI

> An end-to-end sales analytics solution built in Power BI, transforming raw retail transaction data into executive-ready insights with time-series forecasting, KPI monitoring, and regional performance analysis.

![Dashboard Preview](./StoreSales_dashboard11.png)

---

## 📊 Project Overview

This project analyzes **2 years of retail sales data (2019–2020)** across multiple product categories, customer segments, and U.S. states. The dashboard enables business stakeholders to monitor performance, identify trends, and make data-driven decisions — all from a single interactive interface.

### Live KPIs at a Glance

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $341K |
| 📦 Total Orders | 5,000 |
| 📈 Total Profit | $27K |
| 🚚 Avg. Ship Days | 4 Days |

---

## 🗂️ Dashboard Pages

### Page 1 — Sales Performance Dashboard
A comprehensive overview of store performance with multiple visual perspectives:

- **Sales by Category** — Office Supplies ($0.15M) leads, followed by Furniture ($0.11M) and Technology ($0.09M)
- **Sales by Sub-Category** — Top performers: Chairs (46K), Binders (43K), Phones (43K)
- **Sales by Ship Mode** — Standard Class dominates at 78K; Same Day at 7K
- **Sales by Region** — East (48%), Central (33%), South & West breakdown
- **Sales by Segment** — Consumer (48%), Corporate (33%), Home Office (20%)
- **Sales by Payment Mode** — COD (41%), Online (39%), Cards (20%)
- **Monthly Sales & Profit Trend** — Year-over-year comparison (2019 vs 2020)
- **Profit & Sales by State** — Geospatial map visualization using Microsoft Bing

### Page 2 — 10-Day Sales Forecast
A dedicated forecasting page for short-term sales planning:

- **Time-Series Forecast Chart** — Historical trend (Jan 2019 – Dec 2020) + 10-day forward projection
- **Zoomed Forecast View** — Focused view on the Sep–Jan window for granular forecasting
- **Sales by State Bar Chart** — State-level ranking; California leads at $0.34M, followed by New York ($0.19M) and Texas ($0.12M)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development, DAX measures, forecasting |
| **Power Query (M Language)** | Data transformation and ETL |
| **DAX** | Custom KPI calculations and time intelligence |
| **Microsoft Bing Maps** | Geospatial visualization |
| **Excel / CSV** | Source data |

---

## 🔍 Key Insights & Business Findings

1. **Office Supplies drives the highest revenue** despite lower price points — indicating high order volume from corporate buyers.
2. **Standard Class shipping** accounts for the majority of orders (78K), suggesting cost-sensitivity among customers.
3. **COD is the most preferred payment method** (41%), which may present a cash-flow opportunity if incentives shift customers to online payments.
4. **California alone contributes $0.34M** — nearly double New York ($0.19M), highlighting geographic revenue concentration.
5. **Consumer segment at 48%** is the largest — targeted marketing here can yield the highest ROI.
6. **Profit dips mid-year** (visible in monthly trend) — potential for seasonal promotional strategies.
7. **10-day forecast** shows sales stabilizing around 9K–11K range, with a December uptick — consistent with holiday retail patterns.

---

## 📁 Project Structure


super-store-sales-dashboard/
│
├── SuperStoreSales.pbix        # Power BI project file
├── SuperStoreSales_data.csv    # Raw dataset
├── StoreSales_dashboard11.pdf  # Dashboard export (PDF)
├── README.md                   # Project documentation
└── screenshots/
    ├── dashboard_overview.png
    └── forecast_page.png


---

## 🚀 How to Run

1. **Clone the repository**
   bash
   git clone https://github.com/yourusername/super-store-sales-dashboard.git
  

2. **Open in Power BI Desktop**
   - Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   - Open SuperStoreSales.pbix

3. **Refresh Data** (if using your own dataset)
   - Go to Home → Transform Data → Data Source Settings
   - Update the file path to your CSV

4. **Explore the Dashboard**
   - Use region/year filters to drill down
   - Navigate between the Sales and Forecast pages

---

## 📐 Data Model

- **Fact Table:** Orders (Order ID, Sales, Profit, Quantity, Discount)
- **Dimensions:** Customer, Product, Ship Mode, Region, Date
- **Date Table:** Custom DAX calendar table for time intelligence
- **Relationships:** Star schema design for optimized query performance

---

## 🎯 Skills Demonstrated

- ✅ Power BI dashboard design & UX layout
- ✅ DAX calculations (YoY, running totals, KPI cards)
- ✅ Power Query for data cleaning and transformation
- ✅ Time-series forecasting using built-in Power BI analytics
- ✅ Geospatial mapping (Bing Maps integration)
- ✅ Business insight extraction from raw transactional data
- ✅ Executive-level storytelling with data

---

## 📬 Contact

**Sai Vasanth Srungarapu**
📧 saivasanth9701@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/sai-vasanth-srungarapu-373550282/)
🐙 [GitHub]()

---

⭐ *If you found this project useful, consider giving it a star!*
