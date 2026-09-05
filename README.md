# Mobile-Sales-Performance-BI-Dashboard
Interactive Power BI dashboard built on an automated ETL pipeline, tracking $68M+ in sales across 5 mobile brands (Apple, Samsung, Vivo, OnePlus, Xiaomi) and 12+ Indian cities. Built with MySQL, Power Query, SQL, and DAX.

# 📱 Mobile Sales Performance BI Dashboard

An interactive Power BI dashboard built on an automated ETL pipeline, tracking $68M+ in mobile phone sales across 5 major brands and 12+ Indian cities.

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/51e4f50f-48f2-4337-9da2-5be6e08b0049" />


---

## 📌 Problem Statement

A mobile retail business needs visibility into which brands, models, cities, and payment methods are actually driving sales — and how performance is trending over time. This dashboard answers:

- Which brands and mobile models generate the most revenue?
- How are sales distributed geographically across Indian cities?
- Is quantity sold trending up or down year-over-year?
- What payment methods do customers prefer, and how satisfied are they (ratings)?
- Which days of the week see the highest sales activity?

---

## 📊 Dataset

- **Scale:** 68.28M+ in total sales · 1,672 units sold · 331 transactions
- **Brands covered:** Apple, OnePlus, Samsung, Vivo, Xiaomi (5 brands)
- **Geography:** 12+ Indian cities (Delhi, Mumbai, Chennai, Kolkata, and more)
- **Fields:** brand, mobile model, customer name/age, city, price per unit, payment method, transaction date, customer rating

---

## 🛠️ Tools & Tech Stack

| Category | Tools |
|---|---|
| Data Source | MySQL |
| ETL / Data Transformation | Power Query, SQL |
| Dashboard & Visualization | Power BI |
| Calculations / KPIs | DAX |

---

## 🔍 Approach

1. **ETL Pipeline** — Built an automated pipeline to extract raw sales data from MySQL and transform it using Power Query (cleaning, city/brand standardization, date formatting).
2. **Data Modeling** — Structured relationships between sales, customer, and product tables; built DAX measures for KPIs including total sales, average sale value, and quantity by day.
3. **Dashboard Design** — Built an interactive single-page dashboard with brand, customer, and mobile model filters, plus a geographic map view and monthly slicer.

---

## 💡 Key Findings

### 🏆 Brand Performance
- **Apple leads in total sales (₹1.54Cr+)** despite Samsung selling more units (327 vs Apple's 361) at a lower average price point — indicating **Apple drives more revenue per unit sold**.
- **Samsung has the highest transaction count (71)** among all brands, suggesting strong repeat purchase or broader customer base.

### 📉 Quantity Trend (2022–2024)
- **Total quantity sold has declined year-over-year**: 604 units (2022) → 545 units (2023) → 523 units (2024) — a **~13% drop over 2 years**, worth investigating for causes (market saturation, pricing, competition).

### 📱 Top Mobile Models
- **Vivo S1 and Vivo Y51 are the top-selling models** (4.6M each in sales), followed by Vivo V20 and Redmi Note series (~3.6M) — Vivo dominates the top of the model-level leaderboard despite Apple leading at the brand level.

### 💳 Payment Methods
- Sales are **fairly evenly split across UPI (26.67%), Cash (~26%), and Debit Card (25.33%)**, with Credit Card slightly behind — showing no single dominant payment preference, useful for prioritizing which payment rails to support.

### ⭐ Customer Ratings
- **The majority of customers rate their purchase a 5 (82 ratings)**, followed by 4-star (61) — overall sentiment skews strongly positive, with very few 1–2 star ratings (27 combined).

### 📅 Sales by Day
- **Sales are highest at the start of the week (Monday)** and taper off through the week — a pattern worth using for staffing or promotional timing decisions.

---

## 📷 Dashboard View

| Page | Preview |
|---|---|
| Overview | `assets/overview.png` |

*(Replace with your actual screenshot file — see setup instructions below)*

---

## 🚀 How to View

1. Download the `.pbix` file from this repo (https://drive.google.com/file/d/1TW6ZLy6lVhh9mOH6sEK6WKR31AmxNZW2/view?usp=sharing)
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

---

## 🔮 What I'd Improve Next

- Add a year-over-year brand comparison to see which specific brands are driving the overall quantity decline
- Break down the "Total_Sales by City" map by brand to identify regional brand preferences
- Add a customer age/segment view to see if ratings or spending differ by demographic

---

## 👤 Author

**Srushti Pawar**
[LinkedIn](https://linkedin.com/in/srushtipawar9) · [GitHub](https://github.com/srushtipawar9)
