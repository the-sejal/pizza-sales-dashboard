# pizza-sales-dashboard
# 🍕 Pizza Store Sales Performance & Operations Analytics (Excel MIS Dashboard)

An end-to-end Management Information Systems (MIS) and data analytics project built entirely in **Microsoft Excel**. This project transforms raw restaurant transaction logs into clean, visual, and operational reports that help fast-casual dining management optimize staffing schedules, streamline menu choices, and align inventory supply chains with daily demand patterns.

---

## 🛑 Business Problem Statement

A fast-casual pizza franchise processes thousands of order rows every month across multiple categories, crust types, and sizes. Without a centralized, automated MIS report, store management deals with critical revenue leaks and operational guesswork in three primary areas:

* **Inaccurate Staffing Schedules:** Management relies on guesswork instead of tracking peak traffic hours. This causes under-staffing during unexpected rush hours (leading to long customer wait times) and over-staffing during slow periods (wasting payroll budget).
* **Inventory Spoilage & Stockouts:** Kitchen prep teams struggle to forecast ingredient requirements for different pizza sizes and categories. This leads to costly food spoilage for slow-moving items and sudden stockouts for high-demand lines.
* **Low-Margin Menu Layout Blocks:** Niche, low-selling items take up the same kitchen shelf real estate and marketing layout space as active revenue drivers, lowering overall turnover velocity.

**Project Objective:** Build a clean, Excel-based MIS dashboard to process point-of-sale logs, establish key performance indicators (KPIs), map peak traffic trends, and isolate item popularity rankings to maximize store profit margins.

---

## 📋 MIS Report System & Chart Requirements

The Excel data architecture is designed to satisfy two structural analytical phases:

### Phase 1: KPI Metrics
To gain total visibility into baseline store performance, the system calculates the following core business metrics:
1. **Total Revenue:** The exact mathematical sum of the total price of all cleared pizza orders.
2. **Average Order Value (AOV):** The average amount spent per order, calculated by dividing the total revenue by the total number of orders placed.
3. **Total Pizzas Sold:** The sum of the quantities of all individual pizzas sold.
4. **Total Orders:** The aggregate count of all individual orders placed.
5. **Average Pizzas Per Order:** The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.

### Phase 2: Visual Chart Requirements
To uncover hidden purchase patterns, the dashboard deploys seven targeted visual representations:
1. **Daily Trend for Total Orders:** A bar chart displaying daily total orders over time to identify weekly volume fluctuations.
2. **Hourly Trend for Total Orders:** A line chart illustrating hourly trends throughout the operating day to map peak bottleneck hours.
3. **Percentage of Sales by Pizza Category:** A pie chart showing the distribution of sales across different pizza categories to measure performance contributions.
4. **Percentage of Sales by Pizza Size:** A pie chart representing sales attributed to different pizza sizes to track customer dimension preferences.
5. **Total Pizzas Sold by Pizza Category:** A chart presenting the total number of pizzas sold per category to directly compare volume performance.
6. **Top 5 Best Sellers by Total Pizzas Sold:** A bar chart highlighting the top 5 best-selling pizzas based on unit volumes to identify menu anchors.
7. **Bottom 5 Worst Sellers by Total Pizzas Sold:** A bar chart showcasing the bottom 5 worst-selling pizzas to target underperforming menu items.

---

## 💵 Macro Financial & Portfolio Baselines

By aggregating raw point-of-sale data records, the Excel analytical engine establishes a unified baseline for store tracking:
* **Total Gross Revenue:** Accumulated at **\$69,793** across the tracking window.
* **Total Cleared Transactions:** **1,845 total separate orders** successfully fulfilled.
* **Dispersal Volume:** **4,232 individual pizzas sold**.
* **Average Order Value (AOV):** Set firmly at **\$37.83** per customer ticket.
* **Items Per Ticket Density:** A reliable average run rate of **2.29 pizzas per order**.

---

## 📈 Deep Operational Insights

### 🔄 1. Busiest Days & Peak Traffic Hours
* **Weekly Trend Vectors:** Order velocity surges drastically over the tail end of the week. **Friday takes the absolute peak baseline with 330 total orders**, closely followed by Thursday (329) and Saturday (303). Monday (220), Tuesday (242), and Wednesday (222) remain stable, while Sunday drops to the store's minimum run rate of 199 orders.
* **Hourly Traffic Spikes:** Customer demand features a clear **bimodal (two-peak) distribution**:
  * **Primary Lunch Peak (12:00 PM – 1:00 PM):** Clears exactly 206 orders as working professionals look for quick meal options.
  * **Secondary Dinner Peak (5:00 PM – 6:00 PM):** Clears a peak baseline of 208 orders driven by evening family checkout patterns.
  * Sales experience a steep drop-off after 9:00 PM (Hour 21), bottoming out near store closure milestones.

### 🍕 2. Pizza Category & Size Breakdown Matrix
Cross-tabulating transaction mix data points establishes a clear roadmap of customer choices:
* **Category Share Performance:** **Classic Pizza leads the store portfolio at 26.68% contribution share** (1,257 total units sold). Supreme checks in securely at 25.69% (1,044 sold), Veggie tracks at 24.44% (1,018 sold), and Chicken maps as the lowest-volume category at 23.20% share (913 units sold).
* **Sizing Footprint Metrics:** **Large pizzas completely dominate customer choice at 46.42% share**, while Medium holds a stable secondary baseline of 30.01%. Regular sizes represent a 21.64% baseline footprint, while XL (1.83%) and XXL (0.10%) exist only as minor anomalies.

---

## 🏆 Menu Performance Standings (Best vs. Worst Sellers)

Filtering row volumes for separate product lines exposes item popularity variations across the current menu landscape:

**Dashboard Preview**

![Dashboard Snapshot]()
