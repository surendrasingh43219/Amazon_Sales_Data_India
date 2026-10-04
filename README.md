# 📊 Amazon India E-Commerce Sales & Executive Performance Dashboard

[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-in/microsoft-365/excel)
[![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FFB900?style=for-the-badge&logo=powerbi&logoColor=black)](#)
[![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=google-analytics&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **Interactive Executive Management Dashboard** analyzing **10,000+ e-commerce orders** and **₹155.8M ($1.87M+) gross revenue** across India (Jan 2024 – Aug 2026). Engineered to provide senior executive leadership with strategic visibility into sales trends, net margins, category mix, order leakage funnels, fulfillment channels, and regional geographic penetration.

---

## 📌 Executive Summary

This business analytics project delivers a complete management reporting solution designed for non-technical senior executives (such as Operations and Business Unit Managers). The dashboard transforms granular e-commerce transactional data into high-impact, visual KPIs and strategic business recommendations.

### 🎯 Core Business Objectives
1. **Financial Health & Trajectory:** Evaluate monthly revenue run-rates, net margin consistency, and seasonal sales spikes across 32 continuous months.
2. **Product & Category Portfolio:** Identify top revenue drivers and assess portfolio balance across high-ASP electronics vs. high-velocity consumables.
3. **Fulfillment Health & Revenue Loss:** Pinpoint leakage from order cancellations and customer returns to quantify financial damage and isolate root causes.
4. **Channel Economics & Regional Footprint:** Assess the efficiency of logistics fulfillment routes (FBA vs. Seller Flex vs. FBM), payment mode adoption (UPI vs. COD), and top state markets.

---

## 🖥️ Executive Dashboard Overview



## 📈 Key Performance Indicators (At a Glance)

| Metric | Figure (INR) | Normalized Value | Strategic Significance |
| :--- | :---: | :---: | :--- |
| **Total Gross Revenue** | **₹155,789,894** | ₹155.79 Million | Robust 32-month multi-category gross merchandise volume |
| **Total Net Profit** | **₹33,167,008** | ₹33.17 Million | Highly disciplined bottom-line earnings |
| **Net Profit Margin** | **21.29%** | ~21.3% | Stable, healthy margin maintained across all seasons |
| **Total Orders** | **10,000** | 10k Orders | Statistically significant transaction sample |
| **Total Units Sold** | **24,926** | 24.9k Units | Average basket depth of ~2.49 items per transaction |
| **Average Order Value (AOV)**| **₹15,579** | ~₹15.6k | Driven by strong electronic ticket size |
| **Order Completion Rate** | **90.15%** | 9,015 Orders | 81.47% Delivered + 8.68% Shipped in active transit |
| **Total Revenue Lost** | **₹15,648,743** | ₹15.65 Million | **9.85%** of gross sales lost via Cancellations & Returns |

---

## 🔍 In-Depth Analytical Deep Dives

### 1. Overall Sales & Profitability Trends (Jan 2024 – Aug 2026)

![Sales & Profit Performance](assets/02_sales_profit_performance.png)

* **Consistent Revenue Run-Rate:** Average monthly revenue consistently stabilizes between **₹4.5M and ₹5.5M**, demonstrating low baseline volatility.
* **Seasonal Demand Surges:**
  * **July Prime Day Spikes:** Noticeable sales peak in **July 2026 (₹6.44M sales, ₹1.33M profit)** and **July 2024 (₹5.74M sales)** driven by mid-year promotional campaigns.
  * **Fiscal Year-End Demand:** Strong March surges observed in **March 2024 (₹5.76M)** and **March 2025 (₹5.20M)**.
* **Margin Discipline:** Operating net margin holds reliably within a tight band of **19.1% – 23.4%** (averaging **21.29%**), confirming stable pricing resilience and absence of destructive discount wars.

---

### 2. Category & Hero Product Dynamics

![Category & Product Performance](assets/03_category_product_performance.png)

| Category | Total Sales (INR) | Sales Share (%) | Net Profit (INR) | Margin (%) | Units Sold | Orders |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Electronics & Mobiles** | ₹123,569,507 | **79.32%** | ₹26,310,257 | 21.29% | 7,579 | 3,045 |
| **Home & Kitchen** | ₹17,973,219 | **11.54%** | ₹3,837,268 | 21.35% | 4,684 | 1,888 |
| **Apparel & Fashion** | ₹9,831,025 | **6.31%** | ₹2,085,354 | 21.21% | 6,452 | 2,580 |
| **Beauty & Personal Care** | ₹2,889,179 | **1.85%** | ₹604,390 | 20.92% | 3,734 | 1,499 |
| **Pantry & Groceries** | ₹1,526,964 | **0.98%** | ₹329,738 | 21.60% | 2,477 | 988 |
| **TOTAL** | **₹155,789,894** | **100.0%** | **₹33,167,008** | **21.29%** | **24,926** | **10,000** |

#### Top 5 Hero SKUs (All Electronics):
1. **Laptop Backpack:** ₹26.53M Sales | ₹5.63M Profit | 1,641 Units
2. **Power Bank 20000mAh:** ₹25.55M Sales | ₹5.50M Profit | 1,573 Units
3. **5G Smartphone:** ₹24.33M Sales | ₹5.11M Profit | 1,478 Units
4. **Wireless Earbuds:** ₹23.85M Sales | ₹5.20M Profit | 1,475 Units
5. **Smartwatch:** ₹23.31M Sales | ₹4.87M Profit | 1,412 Units

> 💡 **Strategic Takeaway:** While Electronics & Mobiles acts as the primary top-line engine, **Apparel & Fashion** drives the highest order transaction count (2,580 orders; 6,452 units) and acts as an essential customer acquisition vehicle.

---

### 3. Customer Order Status & Revenue Loss Funnel

![Order Status & Revenue Loss](assets/04_order_status_revenue_loss.png)

#### Order Status Breakdown:
* **Delivered:** 8,147 orders (**81.47%**) | ₹125,894,210 revenue | ₹29,697,473 profit
* **Shipped (In Transit):** 868 orders (**8.68%**) | ₹14,246,941 revenue | ₹3,469,536 profit
* **Returned:** 485 orders (**4.85%**) | **₹7,960,583 lost revenue**
* **Cancelled:** 500 orders (**5.00%**) | **₹7,688,159 lost revenue**
* **Total Lost Orders:** **985 orders (9.85%)** | **₹15,648,743 Total Gross Loss**

#### Where Is Revenue Leaking?
* **Electronics & Mobiles Accounts for 79.39% of Total Loss:**
  * Cancelled: ₹5,988,042 | Returned: ₹6,435,800 | **Total Lost: ₹12,423,843**
* **Home & Kitchen:** ₹1,774,766 lost (181 orders)
* **Apparel & Fashion:** ₹1,017,577 lost (258 orders — highest unit cancellation rate)
* **Beauty & Personal Care:** ₹297,818 lost (159 orders)
* **Pantry & Groceries:** ₹134,739 lost (87 orders)

---

### 4. Channels, Logistics & Geographic Footprint

![Payment, Fulfillment & Geography](assets/05_payment_fulfillment_geography.png)

#### Payment Method Distribution:
* **UPI (Digital India Dominance):** ₹78.52M Sales (**50.40%**) | 4,972 Orders | 21.2% Margin
* **Credit / Debit Cards:** ₹31.07M Sales (**19.94%**) | 2,074 Orders | 21.0% Margin
* **Cash on Delivery (COD):** ₹23.10M Sales (**14.83%**) | 1,458 Orders | 21.7% Margin
* **Net Banking:** ₹15.42M Sales (**9.90%**) | 1,024 Orders | 21.4% Margin
* **Amazon Pay Later:** ₹7.68M Sales (**4.93%**) | 472 Orders | 22.0% Margin

#### Fulfillment Channel Breakdown:
* **Amazon FBA (Fulfilled by Amazon):** **₹107.53M (69.02%)** | 7,054 Orders | 21.3% Margin
* **Seller Flex:** **₹31.20M (20.03%)** | 1,966 Orders | 21.8% Margin
* **Merchant FBM (Fulfilled by Merchant):** **₹17.06M (10.95%)** | 980 Orders | 20.3% Margin

#### Top 10 State Markets:
1. **Maharashtra:** ₹29.55M (18.97%) | 1,840 Orders
2. **Karnataka:** ₹24.42M (15.67%) | 1,515 Orders
3. **Delhi (NCR):** ₹22.36M (14.35%) | 1,444 Orders
4. **Tamil Nadu:** ₹17.89M (11.48%) | 1,109 Orders
5. **Uttar Pradesh:** ₹14.14M (9.08%) | 991 Orders
6. **Telangana:** ₹13.96M (8.96%) | 906 Orders
7. **West Bengal:** ₹10.86M (6.97%) | 665 Orders
8. **Gujarat:** ₹9.37M (6.01%) | 591 Orders
9. **Rajasthan:** ₹6.62M (4.25%) | 456 Orders
10. **Kerala:** ₹6.61M (4.24%) | 483 Orders

> 📍 **Top 3 Geographic Clusters** (Maharashtra, Karnataka, and Delhi) represent **49.0%** of total pan-India revenue.

---

## 🎯 Strategic Recommendations for Executive Management

1. **Mitigate High-Ticket Electronics Revenue Loss (₹12.4M Recovery Target):**
   * Implement automated **WhatsApp / IVR order confirmation** for electronics orders exceeding ₹10,000.
   * Require an **OTP-based cancellation barrier** once an item enters the packaging stage to reduce buyer remorse.
2. **Convert COD Customers to Prepaid & Pay Later:**
   * COD orders exhibit disproportionately higher return and cancellation vulnerability.
   * Offer small instant cashback or checkout discounts for UPI and Amazon Pay Later to reduce operational logistics cash handling overhead.
3. **Logistics SLA & Fulfillment Migration:**
   * FBM (Merchant Fulfilled) produces the lowest customer margin (20.3%) and slower delivery.
   * Incentivize tier-2 regional sellers to transition to **Amazon FBA** and **Seller Flex** to ensure Prime delivery speed.
4. **Regional Warehousing Optimization:**
   * Prioritize fulfillment capacity and stock allocation in **Mumbai (Bhiwandi)**, **Bengaluru**, and **Delhi-NCR** fulfillment centers to cut transit times into the top 3 demand clusters.
5. **Return Mitigation via Accurate Product Content:**
   * Enrich product listings in Apparel and Electronics with 360-degree interactive images, video unboxings, and verified size fit recommendations.

---

## 🗂️ Data Dictionary & Architecture

The underlying dataset (`Amazon Sales Data India.xlsx`) contains 10,000 transaction rows with 14 standardized features:

| Column Name | Data Type | Description | Sample Values |
| :--- | :--- | :--- | :--- |
| `Order_ID` | String | Unique alpha-numeric order tracking ID | `ORD_000001`, `ORD_000002` |
| `Order_Date` | Date | Timestamp of customer purchase | `2024-01-01`, `2026-08-31` |
| `Category` | Categorical | Primary product classification | `Electronics & Mobiles`, `Apparel & Fashion` |
| `Product` | String | Specific product name / SKU | `Laptop Backpack`, `5G Smartphone` |
| `Quantity` | Integer | Units purchased per transaction | `1`, `2`, `4` |
| `Unit_Price_INR` | Numeric | Base retail price per item (₹) | `₹1,299`, `₹18,499` |
| `Discount_Pct` | Percentage | Promotional discount applied | `5%`, `15%`, `20%` |
| `Total_Sales_INR` | Numeric | Net invoice revenue after discount | `₹4,441.26`, `₹24,330.00` |
| `Profit_INR` | Numeric | Net operating earnings after COGS | `₹1,016.53`, `₹5,109.13` |
| `Payment_Method` | Categorical | Payment gateway / channel | `UPI`, `Credit/Debit Card`, `COD` |
| `Fulfillment` | Categorical | Supply chain channel | `Amazon (FBA)`, `Seller Flex`, `Merchant (FBM)` |
| `Order_Status` | Categorical | Fulfillment lifecycle status | `Delivered`, `Shipped`, `Returned`, `Cancelled` |
| `Ship_State` | Categorical | Destination Indian State / UT | `Maharashtra`, `Karnataka`, `Delhi` |
| `Month` | Date/String | Year-Month grouping format | `2024-01`, `2026-08` |

---

## 🛠️ Tech Stack & Analytical Tools

* **Microsoft Excel:** Data modeling, calculated fields, dynamic formulas (`SUMIFS`, `INDEX/MATCH`, `XLOOKUP`, `COUNTIFS`), Pivot Tables, custom conditional formatting, and interactive management charts.
* **Executive Presentation:** High-definition executive reporting slide deck structured for senior C-suite reviews.
* **Business Analytics:** Funnel analytics, Cohort/Monthly run-rates, Return/Cancellation root-cause loss modeling.

---

## 📁 Repository Structure

```text
├── assets/                                                    # Dashboard visual previews & chart snapshots
│   ├── 01_executive_dashboard_overview.png                   # Hero executive dashboard preview
│   ├── 02_sales_profit_performance.png                        # Monthly sales & profit trend
│   ├── 03_category_product_performance.png                    # Category & top SKU ranking
│   ├── 04_order_status_revenue_loss.png                       # Order status funnel & loss analysis
│   └── 05_payment_fulfillment_geography.png                   # Payment modes, logistics & state breakdown
├── Amazon Sales Data India.xlsx                               # Core Excel Workbook (DATA, SUMMARY_DATA, DESHBOARD)
├── Amazon_India_Executive_Dashboard_Presentation.pdf         # 5-Page Executive Presentation Deck
├── Amazon India Dashboard Sapphire IQ.pdf                     # Business Requirements Document (BRD)
├── .gitignore                                                 # Standard gitignore (protects temp and personal files)
└── README.md                                                  # Comprehensive Project Documentation
```

---

## 🚀 How to Run & Explore

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<surendra_singh>/amazon-sales-executive-dashboard.git
   cd amazon-sales-executive-dashboard
   ```
2. **Open the Excel Dashboard:**
   * Open `Amazon Sales Data India.xlsx` in **Microsoft Excel 2016 or later** (or Microsoft 365).
   * Navigate to the **`DESHBOARD`** tab to interact with visual charts and high-level KPIs.
   * Review **`SUMMARY_DATA`** to inspect the analytical aggregation logic.
   * Inspect **`DATA`** for the complete raw transaction-level dataset.
3. **Review the Executive Deck:**
   * Open `Amazon_India_Executive_Dashboard_Presentation.pdf` to view the presentation prepared for senior leadership.

---

## 🧑‍💻 Author

* **Surendra Singh** — *Business Analyst Intern* | [Sapphire IQ](https://www.sapphireiq.in)
* **Project:** Amazon India Sales & Executive Dashboard (Project 1)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to use this as a reference or portfolio template for business intelligence and data analytics projects.
