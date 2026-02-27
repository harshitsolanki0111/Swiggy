# 🍔 Swiggy Sales Analytics Dashboard

> *Swiggy Karo, Phir Jo Chahe Karo!*

An interactive **Power BI Dashboard** built for Swiggy, delivering deep insights into food order trends, customer spending, city-level performance, and yearly revenue patterns across India.

![Dashboard Preview]()

---

## 🚀 Overview

This dashboard consolidates Swiggy's key business metrics into a single, intuitive view — empowering operations, marketing, and leadership teams to make fast, data-driven decisions.

---

## 📌 Key Features

- **KPI Overview Cards** — Orders Count (149K), Top 10% Customers Revenue (725M), Rating Count (148K)
- **Amount / Quantity Toggle** — Switch between revenue and volume views instantly
- **Top N Sales by City** — Dynamic bar chart with selectable filters (Top 5, 10, 20, 30) showing leading cities: Tirupati (43M), Electronic City (29M), Baner Pune (27M), and more
- **Total Quantity Amount by Year** — Line chart tracking revenue trends from 2018–2021, showing peak in 2018 (~0.4bn) and decline through 2021
- **Food Category Breakdown** — Veg (122M orders, avg ₹182.11), Non-Veg (106M orders, avg ₹231.81), Others (24M orders, avg ₹50.38)
- **Dynamic Top N Filter Panel** — Adjustable city ranking view (Default, Top 5, 10, 20, 30)

---

## 🗂️ Project Structure

```
swiggy-sales-dashboard/
│
├── Swiggy_Sales_Dashboard.pbix     # Main Power BI dashboard file
├── data/
│   └── swiggy_sales_data.csv       # Source dataset
├── assets/
│   └── dashboard-preview.png       # Dashboard screenshot
├── docs/
│   ├── Business_Problem_Statement.pdf
│   ├── Project_Overview.pdf
│   ├── CONTRIBUTING.md
│   └── CHANGELOG.md
├── .gitignore
├── LICENSE
└── README.md
```

---

## 📊 Dashboard Metrics Snapshot

| Metric | Value |
|---|---|
| Total Orders | 149K |
| Top 10% Customer Revenue | 725M |
| Total Ratings | 148K |
| Top City by Sales | Tirupati (43M) |
| Highest Avg Price Category | Non-Veg (₹231.81) |
| Peak Revenue Year | 2018 (~0.4bn) |

---

## 🍽️ Food Category Summary

| Category | Total Orders | Avg Price (₹) |
|---|---|---|
| Veg | 122M | 182.11 |
| Non-Veg | 106M | 231.81 |
| Others | 24M | 50.38 |

---

## 🛠️ Tech Stack

- **Visualization:** Microsoft Power BI Desktop
- **Data Source:** CSV / Excel
- **DAX:** Custom measures for KPIs, Top N filters, category averages
- **Power Query:** Data transformation and cleaning

---

## ⚙️ Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/swiggy-sales-dashboard.git
   cd swiggy-sales-dashboard
   ```

2. **Open the dashboard**
   - Launch Power BI Desktop
   - Open `Swiggy_Sales_Dashboard.pbix`

3. **Refresh data** *(if using live data)*
   - Go to **Home → Transform Data → Refresh**

4. **Explore**
   - Use the **Amount / Quantity** toggle to switch between revenue and volume views
   - Use the **Top N panel** (Default / Top 5 / 10 / 20 / 30) to filter city rankings dynamically

---

## 🔍 Filters & Controls

| Control | Options |
|---|---|
| View Mode | Amount / Quantity |
| Top N Cities | Default / Top 5 / Top 10 / Top 20 / Top 30 |

---

## 📈 Key Insights

- **Tirupati leads** all cities with 43M in sales, significantly ahead of Electronic City (29M)
- **Non-Veg orders** command the highest average price (₹231.81), indicating premium spend behaviour
- **Revenue peaked in 2018** (~0.4bn) and has steadily declined through 2021 — signalling need for customer retention strategies
- **Veg category dominates** in volume (122M orders) but is priced lower than Non-Veg
- **Top 10% of customers** account for 725M in revenue, highlighting the value of high-LTV customer retention



## 👤 Author

**Your Name**
📧 tharshitsolanki@gmail.com
🔗 [LinkedIn](www.linkedin.com/in/harshit0111) | [GitHub](https://github.com/harshitsolanki0111)

---

> *Built with ❤️ using Microsoft Power BI*
