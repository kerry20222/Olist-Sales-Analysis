# 🛒 Olist E-Commerce Analytics Dashboard

## 📖 Project Overview
This project is an interactive **Olist E-Commerce Analytics Dashboard** built using **Microsoft Power BI**. The dashboard provides a comprehensive macro and micro-level analysis of a large-scale Brazilian marketplace, helping stakeholders monitor commercial health, evaluate customer behavior, and optimize supply chain operations. It transforms raw marketplace transaction data into actionable business intelligence to drive revenue growth and operational efficiency.

---

## ❓ Problem Statement
For e-commerce platforms and marketplace managers, keeping track of multi-vendor operations across vast geographical distances involves juggling complex variables like shipping times, freight costs, payment preferences, and varying customer review scores. Manually analyzing these patterns makes it difficult to pinpoint systemic bottlenecks.

This dashboard aims to solve that problem by visualizing key commercial indicators, allowing stakeholders to:

- 📉 Track Revenue and Traffic Growth across different calendar timelines.
- 💳 Monitor Delivery Latency and understand its direct impact on customer loyalty.
- 🌍 Map Customer and Seller Concentration across different states and major Brazilian hubs.
- 📦 Assess Shipping Burdens by examining the relationship between product prices and freight contributions.
- 📊 Evaluate Category and Vendor Success to isolate top revenue-driving fields.

---

## 📌 Key Metrics
The dashboard tracks several critical performance and marketplace indicators:

- 💵 **Total Revenue:** The aggregate gross merchandise value (GMV) generated on the marketplace.
- 📦 **Total Orders & Products Sold:** The total volume of transactions processed and individual items shipped.
- 🤝 **Average Order Value (AOV) & Average Product Price:** The financial breakdown of consumer spending limits per transaction.
- 👥 **Unique & Repeat Customers:** Metrics tracking total user reach alongside platform customer retention rates.
- 🚚 **Average Delivery Time & Freight %:** Structural logistics KPIs measuring transit speeds and shipping cost overheads.

---

# ✨ Dashboard Features

## 🧮 Executive Overview Dashboard
- **Macro KPI Cards:** Displays real-time calculations for Total Revenue, Total Orders, Average Order Value, and Unique Customers.
- **Revenue & Growth Over Time:** A line chart tracking Total Revenue trends across calendar years.
- **Order Fulfillment Pipeline:** A donut chart tracking order status categories (e.g., Delivered, Shipped, Processing, Canceled).
- **Customer Growth Trends:** A seasonal line chart charting Unique Customers over chronological intervals.
- **Volume Distribution:** A clustered bar chart mapping Products Sold across distinct product categories.

---

## 👥 Customer Analytics Dashboard
- **Retention Core Metrics:** KPI cards isolating Unique Customers, Repeat Customers, Average Order Value, and Average Delivery Time.
- **Customer Retention Split:** A specialized donut chart visualizing the exact ratio of one-time buyers versus loyal Repeat Customers.
- **Geographic Density Map:** A color-filled map tracking regional customer distribution across Brazilian states (`geolocation_state`).
- **Seasonality Track:** A line chart analyzing monthly user activity peaks across `Calendar.Month Number`.
- **City-Level Revenue Leaders:** A clustered bar chart breaking down Total Revenue by top consumption cities (`customer_city`).

---

## 📦 Product & Sales Performance Dashboard
- **Operational KPI Cards:** High-level summaries tracking Products Sold, Total Revenue, Average Product Price, and Freight %.
- **Top Categories by Revenue:** A categorical clustered bar chart sorting and ranking the top revenue-generating item categories.
- **Seller Geography Hubs:** A clustered bar chart identifying Seller Revenue concentrations by vendor city location (`seller_city`).
- **Revenue vs. Freight Analysis:** A scatter chart illustrating the relationship between a product's price and its corresponding shipping freight cost.
- **Pricing Segmentation:** A clustered column chart displaying the complete Product Price Distribution across the marketplace.

---

# 🎛️ Interactive Filters
Users can seamlessly drill down into all data pages using:

- 📅 **Advanced Calendar Slicer** (Year / Month level filtration)
- 📍 **Geographic Slicer** (City-level drilling)
- 🏷️ **Product Category Slicer** (English-translated category fields)

---

# 💡 Key Insights

### 🏙️ Sellers & Regional Hubs
Sales and merchant revenues are highly centralized around specific merchant cities (`seller_city`), indicating a strong reliance on logistics networks branching out from core manufacturing areas like São Paulo.

### 🚚 The Freight Burden
The Revenue vs Freight scatter analysis shows that low-cost items often suffer from disproportionately high freight percentages, heavily influencing cart abandonment and localized category revenue.

### 👥 Customer Loyalty Threshold
The Repeat Customers vs Unique Customer donut split reveals a significant e-commerce reliance on single-transaction buyers, pointing to a strategic opportunity for rolling out customer remarketing campaigns.

### 📈 Logistics Value Loop
Cities with lower Average Delivery Times show a strong correlation with higher spending thresholds and improved transaction density on the regional filled map.

---

# ⚠️ Limitations

- **Geographic Skew:** The data points are heavily concentrated around the southeastern regions of Brazil, meaning insights may not accurately capture purchasing patterns in remote rural territories.

- **Static Snapshot:** The report utilizes a fixed historical Olist dataset slice and does not reflect current real-time economic adjustments or immediate postal rate changes.

- **Data Fields Dependency:** Relies on structural `category_translation` tables to map native item categories into English, meaning unmapped categories are grouped into fallback values.

---

# 🛠️ Tools Used

- 📊 **Power BI** – For interactive data visualization, layout structuring, and theme design.
- 🔄 **Power Query (M)** – For relational schema configuration, missing value corrections, and geo-data normalization.
- 🧠 **DAX (Data Analysis Expressions)** – For programming calculated core measures (Total Revenue, Repeat Customers, Freight %).

---

# 🖼️ Dashboard Preview

> Replace the image paths below with your actual hosted image links or repository paths.

## Executive Overview
![Executive Overview](https://github.com/kerry20222/Olist-Sales-Analysis/blob/main/Images/Executive%20Overview.png)

## Customer Analytics
![Customer Analytics](https://github.com/kerry20222/Olist-Sales-Analysis/blob/main/Images/Customer%20Analytics.png)

## Product & Sales Performance
![Product & Sales Performance](https://github.com/kerry20222/Olist-Sales-Analysis/blob/main/Images/Product%20%26%20Sales%20Performance.png)

---

# 👤 Author
**Mulanga Precious**
