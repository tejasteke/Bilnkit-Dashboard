# 🛒 Blinkit Sales Dashboard (Power BI)

An interactive Power BI dashboard analysing grocery outlet performance for Blinkit — sales by item type, outlet location, outlet size, outlet type, fat content and outlet establishment year.

---

## 📌 Project Overview

The goal of this project is to understand **where and what Blinkit sells** and how outlet characteristics (size, tier, type, age) influence total sales. The dashboard is fully interactive: selecting an **Outlet Size** or **Outlet Type** re-filters every visual and KPI card.

## 📊 Key Metrics (All Outlets)

| KPI | Value |
|---|---|
| Total Sales | ₹1.20M |
| Average Sales | ₹140.99 |
| Number of Items | 8,523 |
| Average Rating | 3.92 ★ |

## 🧰 Tools & Skills

- **Power BI Desktop** — data modelling, DAX measures, interactive visuals, slicers
- Data cleaning and transformation (Power Query)

## 🖥️ Dashboard Components

- **KPI cards** – Total Sales, Avg Sales, No. of Items, Avg Rating
- **Sum of Sales by Item Type and Outlet Location Type** – stacked bar chart (Tier 1 / 2 / 3)
- **Total Sales by Outlet Location Type and Item Fat Content** – clustered bar chart
- **Fat Content** – donut chart (Low Fat vs Regular)
- **Total Sales by Outlet Establishment Year** – area/line chart
- **Sales Based on Outlet Location** – funnel chart (Tier 3 / 2 / 1)
- **Outlet Size** – donut chart (High / Medium / Small)
- **Slicers** – Outlet Size and Outlet Type (Grocery Store, Supermarket Type 1/2/3)

## 💡 Insights

### Overall (no filter)

- The dataset contains **8,523 rows**, with an average rating of **3.92**, average sales of **₹140.99** and total sales of **₹1.20M**.
- **Fruits and Vegetables** have the highest sales among all item types (₹178.12K), closely followed by Snack Foods (₹175.43K).
- Total sales are spread fairly evenly across outlet locations — Tier 3 ₹472.13K, Tier 2 ₹393.15K, Tier 1 ₹336.40K.
- **Fat content:** Low Fat accounts for **64.6%** of sales and Regular for **35.4%**.
- A line chart shows outlet sales based on the **establishment year** of the outlet.
- **Sales by outlet size:**
  - Medium — **42.27%**
  - Small — **37.01%**
  - High — **20.72%**

### Filter: High Outlet Size

- High-size outlets exist **only in Tier 3 and Tier 2 cities** (Tier 3 ₹164.38K, Tier 2 ₹84.61K).
- Regular and Low Fat items contribute almost equally (**50.66% / 49.34%**).
- There are **4 high-size outlets**.
- Total sales: **₹249.0K**.

### Filter: Medium Outlet Size

- **Fruits and Vegetables** contribute the highest sales (₹83.57K).
- Low Fat **66.59%** vs Regular **33.41%**.
- There are **6 outlets**.
- Total sales: **₹507.9K**.

## 📁 Repository Structure

```
├── Blinkit_Dashboard.pbix     # Power BI report file
├── Blinkit_Dashboard.pdf      # Exported dashboard (all filter views)
└── README.md
```

## 🚀 How to Use

1. Download the `.pbix` file and open it in **Power BI Desktop**.
2. Use the **Outlet Size** and **Outlet Type** slicers to filter the dashboard.
3. Hover over any chart for detailed tooltips.

## 👤 Author

**Tejas** — aspiring Data Analyst
🌐 Portfolio: [tejasteke.github.io](https://tejasteke.github.io)

---

⭐ If you found this project useful, consider giving it a star!
"# Bilnkit-Dashboard" 
