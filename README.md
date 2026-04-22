# 📊 Power BI Sales Performance Dashboard

> An interactive Power BI dashboard built on the UCI Online Retail dataset, developed as part of the **TATA Data Visualisation: Empowering Business with Effective Insights** virtual internship on Forage.

---

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `sales-performance-dashboard.pbix` | Power BI report file with all visuals and DAX measures |
| `Online Retail.xlsx` | Source dataset — 541,909 retail transactions across 38 countries |
| `README.md` | Project documentation |

---

## 📌 Project Overview

This project analyzes transactional sales data from a UK-based online retailer covering **December 2010 – December 2011**. The goal is to surface actionable business insights for senior stakeholders through well-designed, data-driven visuals.

The dashboard addresses four key business questions:
1. What are the monthly revenue trends, and which periods drive peak performance?
2. Which countries generate the most revenue (excluding the UK)?
3. Who are the top customers by revenue contribution?
4. Which regions have the highest product demand?

---

## 📁 Dataset Description

**Source:** [UCI Machine Learning Repository — Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)

| Column | Description |
|--------|-------------|
| `InvoiceNo` | Unique invoice number per transaction |
| `StockCode` | Product/item code |
| `Description` | Product name |
| `Quantity` | Units purchased per transaction |
| `InvoiceDate` | Date and time of the transaction |
| `UnitPrice` | Price per unit (GBP £) |
| `CustomerID` | Unique customer identifier |
| `Country` | Country of the customer |

- **Rows:** 541,909 transactions  
- **Countries:** 38  
- **Date Range:** Dec 2010 – Dec 2011  

> **Data Cleaning:** Negative quantities (returns/cancellations) and rows with missing `CustomerID` were excluded from revenue calculations.

---

## 📊 Dashboard Pages & Visuals

### Page 1 — Revenue Trends
- **Line Chart:** Monthly revenue trend for 2011, highlighting seasonality and peak months (Oct–Nov).

### Page 2 — Top Revenue Countries
- **Bar Chart:** Top 10 countries by revenue, excluding the United Kingdom, to identify high-growth international markets.

### Page 3 — Top Customers
- **Column Chart:** Top 10 customers ranked by total revenue, enabling targeted retention strategies.

### Page 4 — Regional Demand
- **Map Visual:** Global product demand by country, visualizing geographic concentration of orders.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — report authoring and DAX measures
- **Microsoft Excel / Power Query** — data cleaning and transformation
- **DAX** — calculated columns and measures (Revenue = Quantity × UnitPrice)

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) — latest version recommended

### Steps
1. Clone or download this repository:
   ```bash
   git clone https://github.com/kadirivinodkumar/Power-bi-sales-dashboard.git
   ```
2. Open `sales-performance-dashboard.pbix` in Power BI Desktop.
3. If prompted, re-point the data source to `Online Retail.xlsx` in the same folder via **Transform Data → Data Source Settings**.
4. Click **Refresh** to reload the data.

---

## 💡 Key Insights

- Revenue peaks sharply in **November 2011**, consistent with pre-holiday purchasing behavior.
- **Netherlands, EIRE (Ireland), Germany, and France** are the strongest international markets by revenue.
- A small group of high-value customers accounts for a disproportionate share of total revenue — a clear opportunity for loyalty programs.
- Demand is heavily concentrated in **Western Europe**, suggesting expansion potential in underserved regions.

---

## 🏆 Certification

This project was completed as part of the **TATA Data Visualisation: Empowering Business with Effective Insights** job simulation on [Forage](https://www.theforage.com/).

**Completed by:** Vinod Kumar  
**Date:** April 22, 2026  
**Skills Demonstrated:** Framing Business Scenarios · Choosing the Right Visuals · Creating Effective Visuals · Communicating Insights and Analysis

---

## 📬 Contact

**Kadiri Vinod Kumar**  
[GitHub](https://github.com/kadirivinodkumar)

---

*⭐ If you found this project useful, consider giving the repo a star!*
