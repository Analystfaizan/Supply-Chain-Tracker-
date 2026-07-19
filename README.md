# 🚚 Supply Chain Tracker

### Power BI | DAX | Power Query | Data Modeling

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/Analystfaizan)
[![DAX](https://img.shields.io/badge/DAX-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/Analystfaizan)
[![Power Query](https://img.shields.io/badge/Power%20Query-blue?style=for-the-badge)](https://github.com/Analystfaizan)

> A **4-page interactive Power BI report** tracking end-to-end supply chain performance — from manufacturing and inventory through to logistics and shipping — giving operations stakeholders a single, real-time view of revenue, stock health, quality, and shipping costs.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Tools & Technologies](#-tools--technologies)
- [Report Structure (4-Page Power BI Report)](#-report-structure-4-page-power-bi-report)
- [Key Metrics & KPIs](#-key-metrics--kpis)
- [Dashboard Preview](#-dashboard-preview)
- [Skills Demonstrated](#-skills-demonstrated)
- [How to Use This Report](#-how-to-use-this-report)
- [Repository Structure](#-repository-structure)
- [About the Author](#-about-the-author)

---

## 🔍 Overview

The **Supply Chain Tracker** is a multi-page Power BI report built to monitor an entire supply chain lifecycle — production, inventory, and shipping — in one connected dashboard. Rather than treating manufacturing, inventory, and logistics as separate reports, this project links them through a shared filter panel and in-report navigation, so stakeholders can move seamlessly between operational areas while keeping the same context (product, location, supplier, transportation mode) applied throughout.

---

## 🎯 Business Problem

Supply chain and operations teams need a fast way to answer:

- Is stock availability keeping pace with demand, and where are we out of stock?
- Which products, suppliers, and locations are driving revenue and unit sales?
- How is manufacturing quality trending — where are defect rates concentrated?
- Which shipping carriers and routes are the most cost-efficient, and how do transportation modes affect lead time?
- Can this be explored interactively across product, supplier, and location without needing a new report for every question?

---

## 🛠 Tools & Technologies

| Category | Tools Used |
|---|---|
| Visualization & Reporting | Power BI |
| Calculations & Metrics | DAX (Data Analysis Expressions) |
| Data Transformation | Power Query |
| Navigation & UX | Custom in-report navigation buttons across 4 report pages |

---

## 📑 Report Structure (4-Page Power BI Report)

### 1️⃣ Executive Summary
Landing page giving a top-line view of the business: revenue by product, customer distribution by revenue, and stock levels by supplier — the starting point for any stakeholder opening the report.

### 2️⃣ Inventory
Tracks stock health across product types, with a Lead Time vs. Order Quantity scatter analysis and a detailed **Stock Level Matrix** (SKU-level stock, order quantity, and lead time).

### 3️⃣ Manufacturing & Quality
Monitors production volume by product type, defect rate performance via a gauge visual, and the relationship between production volume and manufacturing cost.

### 4️⃣ Logistic & Shipping
Analyzes shipping cost by carrier, average shipping time by transportation mode, and total cost by shipping route — helping identify the most cost- and time-efficient logistics options.

**Interactive elements across all pages:**
- 🎚️ Shared filter panel: Product, Location, Supplier Name, Customer Demographics, Transportation Modes
- 🚛 Shipping carrier filters (Select All, Carrier A, Carrier B, Carrier C)
- 📦 Availability status filters (In Stock, Out Stock)
- 🧭 In-report navigation buttons (Home / Inventory / Manufacturing / Logistic) on every page for seamless movement between sections

---

## 💡 Key Metrics & KPIs

| Metric | Value |
|---|---|
| Total Revenue Generated | 578K |
| Total Units Sold | 46K |
| Stock Availability % | 9.50% |
| Defect Rate % | 2.29% |

**Executive Summary highlights:**
- 🧴 Revenue by Product: **Skincare (242K)** leads, followed by Haircare (174K) and Cosmetics (161K)
- 👥 Customer Distribution by Revenue: Unknown 29.97%, Female 27.96%, Male 21.92%, Non-Binary 20.15%
- 📦 Stock levels tracked by supplier, ranging from ~0.65K to 1.14K across suppliers

**Inventory highlights:**
- 📊 Stock Level by Product Type: Haircare and Skincare (1.6K each) slightly ahead of Cosmetics (1.5K)
- ⏱️ Lead Time vs. Order Quantity scatter analysis for demand-planning insight
- 🧾 SKU-level **Stock Level Matrix** — e.g., total stock levels of 4,777 against 4,922 order quantities and 1,708 in lead time across tracked SKUs

**Manufacturing & Quality highlights:**
- 🏭 Production Volume by Product Type: Cosmetics, Haircare, and Skincare each at ~57K units
- ⚠️ Defect Rate gauge: **2.29%** against a 4.58% scale ceiling
- 💰 Production volume plotted against manufacturing cost to spot cost-efficiency outliers

**Logistic & Shipping highlights:**
- 🚚 Shipping Carrier by Cost: Carrier B (0.087K) is the most expensive, Carrier A (0.032K) the most economical
- ✈️ Average shipping time by transportation mode tracked (Air mode analyzed at 0.0051K)
- 🛣️ Cost by Route: Route A (5.8K) carries the highest cost, followed by Route B (4.5K) and Route C (4.3K)

---

## 🖼 Dashboard Preview

### Executive Summary
![Executive Summary](https://github.com/Analystfaizan/Supply-Chain-Tracker-/blob/38e62091aec5509ab933a8aea86f8957c3952adf/Screenshots/Executive_Summery.png)

### Inventory
![Inventory](https://github.com/Analystfaizan/Supply-Chain-Tracker-/blob/38e62091aec5509ab933a8aea86f8957c3952adf/Screenshots/Inventory.png)

### Manufacturing & Quality
![Manufacturing & Quality](https://github.com/Analystfaizan/Supply-Chain-Tracker-/blob/38e62091aec5509ab933a8aea86f8957c3952adf/Screenshots/Manifacturing.png)

### Logistic & Shipping
![Logistic & Shipping](https://github.com/Analystfaizan/Supply-Chain-Tracker-/blob/38e62091aec5509ab933a8aea86f8957c3952adf/Screenshots/Logistick.png)

---

## 🧠 Skills Demonstrated

- Multi-page Power BI report design with shared filter context
- Custom in-report navigation for a seamless, app-like experience
- DAX-driven KPI cards (Revenue, Units Sold, Stock Availability %, Defect Rate %)
- Gauge, scatter, matrix, donut, line, and bar visual design for varied operational data
- Supply chain analytics across manufacturing, inventory, and logistics domains
- Business insight generation for operations and stakeholder reporting

---

## ▶️ How to Use This Report

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Use the top filter panel to narrow by Product, Location, Supplier, Customer Demographics, or Transportation Mode
4. Use the navigation buttons on each page (Home / Inventory / Manufacturing / Logistic) to move between report sections
5. Explore the Stock Level Matrix and shipping visuals for SKU- and route-level detail

---

## 📁 Repository Structure

```
Supply Chain Tracker/
│       
├── Dashboard/                         # Power BI report file
│   ├── Supply Chain Tracker.pbix                             
├── screenshots/                       # Dashboard preview images
│   ├── executive_summary.png
│   ├── inventory.png
│   ├── manufacturing_quality.png
│   └── logistic_shipping.png
├── Source Data/                      #Source Data & Cleaned Data
│   ├── Cleaned_supply_Chain_Data.xlsx
│   ├── Row_Supply Chain Dataset.zip
└── README.md                          # Project documentation
```

*(Update this structure to match your actual repo layout.)*

---

## 👤 About the Author

**Syed Faizan**
Data Analyst | SQL • Power BI • DAX • Excel • Data Visualization

- 📧 Email: sdfaizan3126@gmail.com
- 💻 GitHub: [github.com/Analystfaizan](https://github.com/Analystfaizan)
- 📱 Mobile: +91 8483833126

> Data-driven Computer Science graduate passionate about turning raw data into actionable business insight through dashboards, DAX-based analysis, and exploratory data analysis (EDA).

⭐ **If you found this project useful or interesting, consider starring the repo!**
