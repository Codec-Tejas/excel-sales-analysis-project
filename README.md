# 📊 E-Commerce Sales Analytics Dashboard

> An annual sales performance dashboard built in Microsoft Excel, designed to help business stakeholders monitor revenue trends, understand customer behaviour, and optimize channel strategy across Indian e-commerce marketplaces.

---

## 📌 Project Overview

This project delivers a single-page, interactive **Annual Sales Performance Dashboard** that consolidates a full year of transactional data from an Indian fashion e-commerce retailer. The dashboard surfaces critical business metrics across sales channels, customer demographics, product categories, order fulfilment, and regional performance — enabling leadership teams to make confident, data-backed decisions without digging through raw spreadsheets.

The dashboard is built entirely in **Microsoft Excel** with dynamic slicers for Month, Channel, Category, and Order Status, making it accessible to non-technical stakeholders across the business.

---

## 🧩 Business Problem

The retail business operates across **seven major e-commerce channels** (Amazon, Flipkart, Myntra, Meesho, Ajio, Nalli, and Others) and ships to customers across multiple Indian states. Without a unified view of performance, key questions remained unanswered:

- Which channels are actually driving revenue — and which are underperforming?
- Are we losing orders to cancellations or returns at a concerning rate?
- Who is our core customer, and are we marketing to the right demographic?
- Which states represent our strongest markets, and which are untapped opportunities?
- Why did sales decline in the second half of the year?

This dashboard was built to answer all of the above — in one place, at a glance.

---

## 🎯 Business Objectives

| # | Objective |
|---|-----------|
| 1 | Identify revenue and order volume trends across all 12 months |
| 2 | Evaluate sales performance by channel to guide marketplace investment |
| 3 | Understand the demographic profile of customers (age group & gender) |
| 4 | Assess order fulfilment health — delivered, cancelled, returned, refunded |
| 5 | Rank top-performing states to prioritize regional marketing spend |
| 6 | Surface actionable insights to improve retention and reduce order loss |

---

## 🗂️ Dataset Overview

| Attribute | Detail |
|-----------|--------|
| **Source** | Indian fashion e-commerce retail store |
| **Time Period** | Full calendar year (Jan – Dec) |
| **Records** | ~30,000+ order-level transactions |
| **Geography** | Pan-India (28+ states) |
| **Channels** | Amazon, Flipkart, Myntra, Meesho, Ajio, Nalli, Others |

**Key fields in the dataset:**

`Order ID` · `Customer ID` · `Gender` · `Age` · `Age Group` · `Month` · `Order Status` · `Channel` · `Category` · `Size` · `Quantity` · `Amount (INR)` · `Ship State` · `B2B Flag`

**Product Categories Covered:**  
Kurta · Set · Saree · Western Dress · Top · Blouse · Bottom · Ethnic Dress

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|-----|-------------|
| **Total Revenue (INR)** | Sum of all order amounts across the year |
| **Total Orders** | Count of unique orders placed |
| **Delivery Rate** | % of orders successfully delivered |
| **Cancellation Rate** | % of orders cancelled before fulfilment |
| **Return & Refund Rate** | % of orders returned or refunded post-delivery |
| **Top Channel Share** | Revenue contribution % by marketplace |
| **Women vs. Men Sales Split** | Gender-based revenue share |
| **Top 3 States by Revenue** | Highest-contributing states for strategic focus |
| **Peak Sales Month** | Month with highest order volume and revenue |

---

## 🖥️ Dashboard Features

- **📅 Monthly Trend Chart** — Combined bar and line chart tracking revenue (Sum of Amount) and order volume (Count of Order ID) side by side across all 12 months
- **🍩 Gender Sales Split** — Pie chart breaking down sales between Men and Women customers
- **🟠 Order Status Breakdown** — Pie chart showing the share of Delivered, Cancelled, Returned, and Refunded orders
- **📊 Sales by Channel** — Bar chart ranking all seven marketplaces by revenue contribution percentage
- **👥 Age vs. Gender Orders** — Clustered bar chart comparing order volumes across Adult, Senior Citizen, and Teenager segments, split by gender
- **🗺️ Top 10 States by Revenue** — Horizontal bar chart ranking the highest-revenue states
- **🔍 Dynamic Slicers** — Filter the entire dashboard by Month, Channel, Product Category, and Order Status simultaneously

---

## ❓ Business Questions Answered

1. **Which month generated the highest revenue and orders?**  
   → March recorded peak performance in both revenue and order volume.

2. **Which sales channels contribute most to revenue?**  
   → Amazon (35.5%), Myntra (23.4%), and Flipkart (21.6%) together account for over **80% of total revenue**.

3. **Who is the primary customer — men or women?**  
   → Women drive **64% of all sales**, significantly outpacing men at 36%.

4. **Which age group places the most orders?**  
   → The **Adult segment** dominates with ~80% of all orders, far ahead of Senior Citizens and Teenagers.

5. **What is the overall order fulfilment health?**  
   → **92% of orders were successfully delivered**. Cancellations (3%) and refunds (2%) remain low but are monitored.

6. **Which states generate the most revenue?**  
   → **Maharashtra, Karnataka, and Uttar Pradesh** are the top three revenue-generating states.

7. **Did sales decline over the year, and when?**  
   → Yes — sales peaked in March and showed a consistent downward trend through the second half, with the lowest performance in November–December.

---

## 💡 Key Business Insights

### 1. 👩 Women Are the Core Customer Base
Women account for **64% of total sales revenue** — nearly double the male contribution. The product catalogue (kurtas, sets, sarees, ethnic wear) is strongly skewed toward female shoppers. Marketing, promotions, and new product development should be primarily women-centric.

### 2. 🏪 Amazon, Myntra & Flipkart Dominate Revenue
Three platforms collectively contribute **~80% of revenue**:
- **Amazon** — 35.5% (market leader)
- **Myntra** — 23.4% (fashion-focused, high conversion)
- **Flipkart** — 21.6% (strong volume)

Channels like Ajio (6.2%) and Meesho (4.5%) remain underdeveloped and present growth opportunities.

### 3. 🧑 Adults Are the Primary Buying Segment
The **Adult age group (25–60)** drives the majority of orders across both genders, with women adults alone accounting for over **55% of all orders**. Teenager and Senior Citizen segments are comparatively small contributors.

### 4. 📍 Maharashtra, Karnataka & Uttar Pradesh Lead Revenue
These three states are the top revenue contributors nationally:
- **Maharashtra** — Strong urban base (Mumbai, Pune)
- **Karnataka** — Driven by Bengaluru's large digital-native population
- **Uttar Pradesh** — High-volume orders from Lucknow, Varanasi, and Prayagraj

States like Telangana, Tamil Nadu, and West Bengal also show strong performance and merit investment.

### 5. 📉 Second-Half Sales Decline Warrants Investigation
Sales peaked in **March** and declined steadily through the rest of the year. This suggests the business may be seasonal or that mid-year engagement strategies are insufficient to sustain early momentum.

### 6. ✅ High Delivery Rate Is a Competitive Strength
A **92% delivery success rate** is a strong operational signal. However, a combined 5% loss through cancellations, returns, and refunds should be examined at the SKU and channel level to reduce revenue leakage.

---

## 📋 Business Recommendations

| Priority | Recommendation | Expected Impact |
|----------|---------------|-----------------|
| 🔴 High | Launch women-targeted campaigns (especially Sets & Kurtas) on Amazon and Myntra ahead of peak months | Revenue growth in Q1–Q2 |
| 🔴 High | Investigate the March-to-December sales decline — assess if driven by seasonality, catalogue gaps, or competitor activity | Stabilize H2 revenue |
| 🟡 Medium | Increase marketing investment in Maharashtra, Karnataka, and Uttar Pradesh — the proven high-value markets | Revenue concentration in strong zones |
| 🟡 Medium | Develop adult women (25–55) as a loyalty segment through targeted retention programs | Improve repeat purchase rate |
| 🟢 Low | Grow presence on Ajio and Meesho, which have low current share but expanding user bases | Channel diversification |
| 🟢 Low | Analyse the 3% cancellation rate by channel and category to identify product-market fit gaps | Reduce revenue leakage |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, analysis, Pivot Tables, and dashboard design |
| **Excel Slicers** | Interactive filtering for Month, Channel, Category, Status |
| **Excel Charts** | Bar, line, pie, and combo charts for visual storytelling |

---

## 📸 Dashboard Preview

![E-Commerce Sales Analytics Dashboard](dashboard_preview.png)

> *Interactive dashboard with slicers for Month, Channel, Category, and Order Status. All charts update dynamically based on slicer selection.*

---

## ✅ Conclusion

This dashboard transforms raw transactional data into a clear business narrative. The analysis reveals that **women adults purchasing through Amazon, Myntra, and Flipkart** represent the highest-value customer segment, concentrated in three key states. While the business demonstrates strong operational delivery performance, the mid-year sales decline and channel concentration across three platforms highlight areas requiring strategic attention.

The dashboard equips business stakeholders with the visibility needed to optimize channel investment, refine customer targeting, and build a more consistent annual revenue trajectory.

---

## 📁 Repository Structure

```
📦 ecommerce-sales-dashboard
├── README.md
├── data/
│   └── dataset.xlsx
│
├── dashboard/
│   ├── E-Commerce_Sales_Analytics_Dashboard.xlsx
│   └── Dashboard.png                        

```

---

## 👤 Author

**Tejas Salunkhe**  
Aspiring Data Analyst  |  Business Intelligence Enthusiast 
🔗 [LinkedIn](https://linkedin.com/in/tejassalunkhe) · [GitHub](https://github.com/Codec-Tejas)

---

