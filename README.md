# 🟡 Blinkit Sales Dashboard — Power BI

A single-page executive overview dashboard built in **Microsoft Power BI** that analyzes sales performance, customer feedback, order trends, and delivery operations for **Blinkit** — India's quick-commerce grocery delivery platform.

## 📊 Dashboard Preview

> Open `sales_dashboard_of_blinkit.pbix` in Power BI Desktop to interact with the full dashboard.

## 📁 Project Structure

    sales_dashboard_of_blinkit.pbix   # Main Power BI report file
    README.md                         # Project documentation

## 🗂️ Data Model

The report is built on **four core tables**:

| Table | Description |
|---|---|
| `blinkit_orders` | Order-level records including order ID, month, payment method, and order total |
| `blinkit_order_items` | Line-item details including product quantity and revenue per order |
| `blinkit_customer_feedback` | Customer ratings and sentiment scores per order |
| `blinkit_delivery_performance` | Delivery status and performance metrics per order |

## 📈 Dashboard Page: Executive Overview

The report contains a single executive-level page with the following visuals:

### KPI Cards
- **Total Revenue** — Sum of revenue across all order items
- **Total Orders** — Count of unique order IDs
- **Average Rating** — Mean customer rating
- **Total Quantity Sold** — Sum of items delivered

### Charts & Visuals

| Visual Type | Insight |
|---|---|
| 📊 Clustered Column Chart | Monthly order totals over time |
| 📉 Area Chart | Revenue trend across months |
| 🍩 Donut Chart | Payment method breakdown |
| 🥧 Pie Chart | Delivery status distribution |
| 🔻 Funnel Chart | Customer sentiment funnel |
| 🔡 Word Cloud | Customer feedback keyword analysis (custom visual) |
| 🔽 Slicer | Interactive month-name filter |

## 🔑 Key Metrics Tracked

- `order_total` — Revenue per order
- `TOTAL REVENUE` — Aggregated item-level revenue
- `quantity` — Units sold per order
- `rating` — Customer satisfaction score
- `payment_method` — Cash, UPI, card, etc.
- `delivery_status` — On-time, delayed, failed, etc.
- `sentiment` — Positive / Neutral / Negative classification

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Report building and data modelling
- **DAX (Data Analysis Expressions)** — Measures and calculated columns
- **Power Query (M)** — Data transformation and loading
- **Custom Visual: Word Cloud** — `WordCloud1447959067750` from AppSource

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)

### Steps
1. Clone or download this repository
2. Open **Power BI Desktop**
3. Go to **File → Open** and select `sales_dashboard_of_blinkit.pbix`
4. The dashboard will load with all visuals and data pre-embedded
5. Use the **Month Name slicer** to filter the view by time period

## 💡 Insights You Can Derive

- Which months had the highest order volumes and revenue?
- What is the most popular payment method among customers?
- How does delivery performance (on-time vs. delayed) compare across orders?
- What is the overall customer sentiment and average rating?
- Which keywords appear most frequently in customer feedback?

## 📌 Notes

- The data is embedded directly inside the `.pbix` file — no external database connection required.
- The Word Cloud is a **custom visual** sourced from Microsoft AppSource; it may prompt for permission on first load.
- This dashboard was built for **analytical and portfolio purposes** using simulated/sample Blinkit data.

## 🙌 Acknowledgements

- Inspired by Blinkit's real-world quick-commerce operations in India
- Dashboard design follows Power BI best practices for executive reporting
