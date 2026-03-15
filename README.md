# 🍔 Swiggy Sales Performance Dashboard — Excel Business Intelligence Project

> **A comprehensive Excel-powered analytics dashboard dissecting ₹53M in food delivery sales across 197,430 orders, 28 Indian cities, 993 restaurants, and 59,064 unique dishes — built entirely in Microsoft Excel with Pivot Tables, dynamic slicers, and interactive visualizations.**
---
## Dashboard Preview
![Swiggy Dashboard](https://github.com/TofunmiTech01/swiggy-sales-analysis-excel/blob/main/Swiggy-Dashboard.PNG)

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Business Context](#business-context)
- [Dataset Summary](#dataset-summary)
- [Tools & Technologies](#tools--technologies)
- [Dashboard Preview](#dashboard-preview)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Analytical Insights](#analytical-insights)
  - [Monthly Sales Trend](#1-monthly-sales-trend)
  - [Daily Sales Pattern](#2-daily-sales-pattern)
  - [Weekly Sales Trend](#3-weekly-sales-trend)
  - [Quarterly Performance](#4-quarterly-performance)
  - [Food Type Analysis](#5-food-type-analysis)
  - [Geographic Performance](#6-geographic-performance)
  - [Restaurant Rankings](#7-restaurant-rankings)
  - [Dish & Category Intelligence](#8-dish--category-intelligence)
  - [Rating & Customer Sentiment](#9-rating--customer-sentiment)
- [Strategic Recommendations](#strategic-recommendations)
- [Connect With Me](#connect-with-me)

---

## Project Overview

Food delivery is one of the fastest-moving, most competitive digital markets in India. Understanding *where* sales come from, *when* demand peaks, *which* restaurants and dishes drive the most value, and *how* customer sentiment varies across geographies — these are not nice-to-haves. They are survival intelligence.

This project delivers a fully interactive Excel dashboard analyzing **₹53.01M in Swiggy order data** spanning January to August 2025 — covering **197,430 orders**, **993 restaurants**, **59,064 unique dishes**, and **28 cities** across India. Built entirely in Microsoft Excel using Pivot Tables, GETPIVOTDATA formulas, dynamic slicers, and custom charting, this dashboard proves that world-class business intelligence doesn't require expensive BI tools — it requires analytical rigor and Excel mastery.

---

## Business Context

Swiggy operates in a hyper-competitive Indian food delivery market where margins are thin, customer loyalty is volatile, and geographic demand patterns shift rapidly. The analytical questions this dashboard is designed to answer:

- Which cities and states are the true revenue engines?
- Is there a consistent day-of-week or monthly demand pattern that can be exploited?
- How do the QSR giants (KFC, McDonald's, Pizza Hut) compare against each other?
- Does the Veg/Non-Veg split signal anything about market positioning?
- Are customer ratings consistent across order volumes, or are high-rating restaurants a minority?

---

## Dataset Summary

| Attribute | Detail |
|---|---|
| **Period Covered** | January 2025 – August 2025 |
| **Total Records** | 197,430 rows |
| **Total Orders** | 197,430 |
| **Total Sales** | ₹53,012,505.77 (~₹53.01M) |
| **Unique Restaurants** | 993 |
| **Unique Dishes** | 59,064 |
| **Unique Food Categories** | 4,972 |
| **Cities Covered** | 28 |
| **States Covered** | 28 |
| **Key Fields** | State, City, Order Date, Day, Quarter, Week, Restaurant Name, Location, Category, Dish Name, Food Type, Price (INR), Rating, Rating Count |

---

## Tools & Technologies

- **Microsoft Excel** — End-to-end analytics and dashboard design
- **Pivot Tables** — Multi-dimensional aggregation across all key dimensions
- **GETPIVOTDATA** — Dynamic KPI extraction for dashboard cards
- **Power Query** — Data transformation and computed column generation
- **Excel Slicers** — Interactive filtering by Month, Category, and Restaurant
- **Custom Charting** — Bar, donut, line, map, and column visualizations
- **TEXT / WEEKNUM / IF / SEARCH formulas** — Derived columns (Day, Week, Food Type)
- **Bing Maps Integration** — Geographic sales visualization by Indian state

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---|
| **Total Sales** | ₹53.01M |
| **Total Orders** | 197,430 |
| **Average Order Value (AOV)** | ₹268.51 |
| **Average Rating** | 4.34 / 5.00 |
| **Total Rating Count** | 5.59M |
| **Unique Restaurants** | 993 |
| **Unique Dishes** | 59,064 |
| **Cities Covered** | 28 |
| **Veg Sales Share** | 65.2% |
| **Non-Veg Sales Share** | 34.8% |

---

## Analytical Insights

### 1. Monthly Sales Trend

| Month | Sales (₹) |
|---|---|
| January | 6,825,186 |
| February | 6,269,106 |
| March | 6,573,530 |
| April | 6,594,515 |
| May | 6,793,558 |
| June | 6,514,183 |
| July | 6,650,966 |
| August | 6,791,462 |

**Key Findings:**

- **January is the single strongest month** at ₹6.83M — likely driven by New Year ordering momentum and post-holiday comfort-food demand.
- **February is the weakest month** at ₹6.27M, a 8.1% dip from January — a pattern consistent with shorter month duration and post-January spending pullback.
- **May and August are the two strongest non-January months** (₹6.79M each), suggesting mid-year and late-summer demand spikes — possibly tied to summer heat driving delivery preference over dining out.
- **Monthly sales are remarkably stable**, with the range between the lowest (Feb) and highest (Jan) months being only ₹556K on a ₹53M base — indicating a resilient, year-round demand pattern rather than sharp seasonality.

---

### 2. Daily Sales Pattern

| Day | Sales (₹) | Index vs. Weakest Day |
|---|---|---|
| **Saturday** | 7,782,935 | **+5.7%** |
| Thursday | 7,664,619 | +4.1% |
| Sunday | 7,638,004 | +3.8% |
| Friday | 7,579,993 | +3.0% |
| Wednesday | 7,542,103 | +2.5% |
| Monday | 7,445,437 | +1.2% |
| **Tuesday** | 7,359,414 | — (lowest) |

**Key Findings:**

- **Saturday is the undisputed peak day** at ₹7.78M — consumers are most likely to treat themselves on weekends, order for groups, and explore premium options.
- **The weekend effect is real**: Saturday + Sunday combined = ₹15.42M, representing 29.1% of total weekly sales despite being only 2/7 days (28.6%) — a slight but consistent premium.
- **Tuesday is the weakest day** at ₹7.36M — mid-week ordering fatigue is a real phenomenon. This is the optimal day for targeted promotions and discounts to stimulate demand.
- **The daily sales range is surprisingly narrow** — only a ₹423K spread between the best and worst days, suggesting Swiggy has effectively smoothed demand across the week through promotions, subscriptions, and habit formation.

---

### 3. Weekly Sales Trend

The weekly breakdown across 36 weeks reveals clear patterns:

- **Week 1 is a significant outlier at ₹880,871** — less than 60% of the average weekly sales (₹1,526,838). This reflects a partial first week (January 1st start) rather than genuine demand weakness.
- **Week 8 is the peak week at ₹1,760,217** — almost double Week 1 and 15.3% above the 36-week average. This aligns with mid-February, likely boosted by Valentine's Day ordering.
- **Weeks 2 through 35 show remarkable consistency**, with most weeks falling in the ₹1.45M–₹1.57M band — confirming the platform's structural demand stability.
- **Week 36 shows a sharp drop to ₹201,875** — reflecting that the dataset ends mid-week in late August (partial week), not a true demand collapse.

---

### 4. Quarterly Performance

| Quarter | Sales (₹) | Orders | Avg Rating | Sales Share |
|---|---|---|---|---|
| **Q1** | 19,667,822 | 73,096 | 4.34 | 37.1% |
| **Q2** | 19,902,257 | 74,163 | 4.34 | 37.5% |
| **Q3** | 13,442,427 | 50,171 | 4.34 | 25.4% |
| **Total** | **53,012,506** | **197,430** | **4.34** | 100% |

**Key Findings:**

- **Q1 and Q2 are nearly identical in performance** — both ~₹19.8M in sales with ~73-74K orders — pointing to a consistently strong H1 with no significant seasonal cliff.
- **Q3 appears lower at ₹13.4M** but this is a data artifact: Q3 only covers July and August (2 months vs. 3 months for Q1 and Q2). On a per-month basis, Q3 averages ₹6.72M/month — fully consistent with H1 performance.
- **Average rating holds at exactly 4.34 across all three quarters** — an extraordinary finding. Customer satisfaction is structurally stable and not influenced by volume peaks or seasonal demand shifts.

---

### 5. Food Type Analysis

| Food Type | Sales (₹) | Orders | Sales Share |
|---|---|---|---|
| **Veg** | 34,538,215 | 140,472 | **65.2%** |
| Non-Veg | 18,474,291 | 56,958 | **34.8%** |

**Key Findings:**

- **Veg dominates with 65.2% of total sales** — a reflection of India's large vegetarian population and Swiggy's strong penetration in cities with high Veg preference (Bengaluru, Ahmedabad, Jaipur).
- **Non-Veg punches above its weight in AOV**: Non-Veg orders average higher price points (meat dishes, biryani, chicken buckets), which is why Non-Veg's 28.8% order share translates to a higher 34.8% revenue share.
- **The top revenue-generating dish is Veg** (Bold BBQ Veggie Thin n Crispy at ₹99,617) — but the top restaurant is Non-Veg dominant (KFC at ₹4.25M). This dichotomy signals that Veg wins on volume while Non-Veg wins on individual order value.

---

### 6. Geographic Performance

#### Top 10 Cities by Sales:

| Rank | City | Sales (₹) | State |
|---|---|---|---|
| 1 | **Bengaluru** | 5,456,798 | Karnataka |
| 2 | Lucknow | 3,117,360 | Uttar Pradesh |
| 3 | Hyderabad | 3,021,712 | Telangana |
| 4 | Mumbai | 3,015,573 | Maharashtra |
| 5 | New Delhi | 2,829,181 | Delhi |
| 6 | Ahmedabad | 2,817,836 | Gujarat |
| 7 | Chandigarh | 2,809,441 | Punjab |
| 8 | Kolkata | 2,662,802 | West Bengal |
| 9 | Chennai | 2,642,595 | Tamil Nadu |
| 10 | Jaipur | 2,502,933 | Rajasthan |

#### Bottom 5 States by Sales:

| State | Sales (₹) |
|---|---|
| Odisha | 1,193,585 |
| Tripura | 1,144,272 |
| Mizoram | 824,931 |
| Nagaland | 576,798 |
| Sikkim | 560,965 |

**Key Findings:**

- **Bengaluru is the runaway market leader at ₹5.46M** — 75% higher than the #2 city (Lucknow). As India's tech capital, Bengaluru's young, high-income, time-poor professional demographic is the ideal Swiggy customer: high ordering frequency, premium dish choices, and digital-native behavior.
- **Bengaluru alone accounts for 10.3% of total platform sales** — a significant single-city concentration risk. Any operational disruption or competitive entry in Bengaluru has outsized platform-level impact.
- **Lucknow's #2 ranking is a surprise** — outpacing metro giants like Mumbai, Delhi, and Hyderabad. This signals deep Swiggy penetration in Tier-2 India and the untapped potential of non-metro markets.
- **The top 5 cities (Bengaluru, Lucknow, Hyderabad, Mumbai, New Delhi) together generate ₹17.44M** — 32.9% of total sales from just 5 of 28 cities.
- **The Northeast and smaller states (Sikkim, Nagaland, Mizoram)** represent nascent markets with sub-₹825K in sales — either early-stage penetration or genuine demand gaps requiring tailored local strategies.

---

### 7. Restaurant Rankings

#### Top 10 Restaurants by Total Sales:

| Rank | Restaurant | Sales (₹) | Share of Total |
|---|---|---|---|
| 1 | **KFC** | 4,246,952 | **8.0%** |
| 2 | McDonald's | 3,343,095 | 6.3% |
| 3 | Pizza Hut | 2,133,266 | 4.0% |
| 4 | Burger King | 1,900,817 | 3.6% |
| 5 | Domino's Pizza | 1,834,022 | 3.5% |
| 6 | Olio - The Wood Fired Pizzeria | 1,236,369 | 2.3% |
| 7 | LunchBox - Meals and Thalis | 1,101,141 | 2.1% |
| 8 | Baskin Robbins | 860,592 | 1.6% |
| 9 | Faasos - Wraps, Rolls & Shawarma | 780,215 | 1.5% |
| 10 | The Good Bowl | 673,343 | 1.3% |

**Key Findings:**

- **The top 5 restaurants are all Western QSR giants** — KFC, McDonald's, Pizza Hut, Burger King, and Domino's — collectively generating ₹13.46M (25.4% of total platform sales) from just 5 of 993 restaurants. This is extraordinary concentration.
- **KFC alone at ₹4.25M generates more than the bottom ~700 restaurants combined** — a power-law distribution that is typical in food delivery platforms but remarkable in its severity here.
- **Olio at #6 (₹1.24M) is the highest-ranked non-QSR/chain restaurant**, suggesting that premium, niche dining concepts can compete with global chains on delivery platforms when the product is right.
- **LunchBox's #7 ranking** (₹1.10M) highlights strong demand for affordable, everyday meal solutions — the "office lunch" segment is alive and thriving on delivery platforms.
- The **remaining 983 restaurants share ₹39.55M** (74.6% of sales), averaging ₹40,235 per restaurant — a market with a long, profitable tail.

---

### 8. Dish & Category Intelligence

#### Top 10 Dishes by Sales:

| Rank | Dish | Sales (₹) | Type |
|---|---|---|---|
| 1 | Bold BBQ Veggie Thin n Crispy | 99,617 | Veg |
| 2 | Korean & Thai Roll Chicken Meal | 95,592 | Non-Veg |
| 3 | Full House Popcorn Chicken Bucket | 79,200 | Non-Veg |
| 4 | Triple Chicken Feast | 70,757 | Non-Veg |
| 5 | Indian Tandoori Roll Chicken Meal | 70,392 | Non-Veg |
| 6 | Big 12 - Chicken Bucket | 69,738 | Non-Veg |
| 7 | Veggie Supreme | 67,841 | Veg |
| 8 | Paneer Butter Masala | 67,412 | Veg |
| 9 | Hot & Crispy Chicken - 8 pcs | 67,360 | Non-Veg |
| 10 | Ultimate Savings Chicken Bucket | 64,612 | Non-Veg |

#### Top Categories by Sales:

| Category | Sales (₹) | Orders | AOV (₹) |
|---|---|---|---|
| **Recommended** | 7,188,937 | 24,100 | 298.30 |
| Main Course | 760,045 | 2,959 | 256.86 |
| Burger Combos (3 Pc Meals) | 507,774 | 1,331 | 381.50 |
| McSaver Combos (2 Pc Meals) | 431,697 | 1,885 | 229.02 |
| Desserts | 416,311 | 2,944 | 141.41 |

**Key Findings:**

- **"Recommended" is the top category by a massive margin at ₹7.19M** — more than 9x the next category. This reflects Swiggy's algorithmic curation power: when the platform recommends a dish, customers follow. It also shows that restaurants investing in getting their items into Swiggy's "Recommended" section gain a disproportionate commercial advantage.
- **The #1 dish is Veg** (Bold BBQ Veggie Thin n Crispy at ₹99,617) — consistent with the broader 65% Veg sales dominance, but notable that even in the top 10 dishes, Veg and Non-Veg are roughly split 3:7 by count.
- **Paneer Butter Masala at #8 (₹67,412)** — India's most iconic comfort dish is a top-10 performer on a delivery platform dominated by Western QSRs. Local cuisines and traditional dishes hold their own even against premium international brands.
- **Bucket meals and combo formats dominate** the top dish list — consumers on delivery platforms optimize for value-per-rupee, favoring sharing-sized, combo-priced items over individual premium dishes.
- **Freshly Scooped Tubs (Baskin Robbins) have the highest category AOV at ₹414** — premium dessert categories carry the highest average ticket size, a lever that can be activated through upsell and pairing strategies.

---

### 9. Rating & Customer Sentiment

| Rating Range | Orders | Share |
|---|---|---|
| 4.5 – 5.0 | 43,859 | **22.2%** |
| 4.0 – 4.5 | 125,136 | **63.4%** |
| 3.0 – 4.0 | 24,257 | 12.3% |
| 2.0 – 3.0 | 3,707 | 1.9% |
| Below 2.0 | 471 | 0.2% |

**Key Findings:**

- **85.6% of all orders carry a rating of 4.0 or above** — an overwhelmingly positive sentiment profile that signals strong platform-wide quality control and customer satisfaction.
- **The platform average of 4.34/5.00 is maintained consistently across all three quarters** — this is not an aggregated average masking volatility. It is genuinely stable satisfaction at scale.
- **Only 2.1% of orders fall below a 3.0 rating** — a remarkably low dissatisfaction rate for a platform handling 197,430 orders across 993 restaurants, 28 cities, and 59,064 dishes. It suggests either strong quality filtering, biased upward rating behavior, or both.
- **The 5.59M total rating count** dwarfs the 197,430 orders — because Rating Count reflects cumulative historical reviews on each dish/restaurant, not just reviews for this dataset's orders. This makes it a powerful proxy for restaurant reputation depth and social proof.

---

## Strategic Recommendations

### 1. Double Down on Bengaluru — But Diversify the Dependency
Bengaluru at ₹5.46M is 75% ahead of its nearest competitor. Protect this market aggressively — but the concentration risk is real. Build operational redundancy and accelerate growth in Lucknow (#2 at ₹3.12M) and Hyderabad (#3 at ₹3.02M) to create a more balanced top-tier portfolio.

### 2. Invest in Tier-2 City Expansion
Lucknow's surprise #2 ranking is a strategic signal. Cities like Jaipur, Chandigarh, and Ahmedabad — all generating ₹2.5–2.8M — show that non-metro India has genuine, scalable delivery demand. A targeted Tier-2 expansion playbook could unlock the next wave of platform growth.

### 3. Activate Tuesday With Targeted Promotions
Tuesday is the platform's weakest day (₹7.36M vs. ₹7.78M on Saturday). A Tuesday-specific deal — flash discounts, free delivery, loyalty point multipliers — could close a significant portion of that gap and improve weekly revenue consistency.

### 4. Leverage Veg Leadership for Premium Positioning
With 65.2% of sales from Veg items, Swiggy has a dominant Veg customer base. But Non-Veg's higher AOV means there's a revenue-per-order gap. Strategies to grow Veg AOV through premium Veg categories (gourmet, organic, artisanal) could unlock significant incremental revenue without cannibalizing the existing base.

### 5. "Recommended" Section is the Platform's Biggest Revenue Lever
The "Recommended" category at ₹7.19M — dwarfing every other category — is the single most powerful commercial lever on the platform. Restaurants should be guided on how to qualify for this section; Swiggy should consider a transparent "Recommended" criteria framework that incentivizes quality investment.

### 6. 🍗 KFC's ₹4.25M Dominance is a Partnership Asset — and a Risk
KFC alone = 8% of total platform sales. This is both a major partnership win and a single-point-of-failure. Diversify the top-restaurant portfolio by actively growing mid-tier restaurant brands (like Olio, LunchBox) to reduce QSR concentration while maintaining overall platform health.

### 7. Replicate Week 8's Valentine's Spike Intentionally
Week 8 (mid-February) at ₹1.76M is the highest week of the dataset — likely driven by Valentine's Day demand. Build a structured "peak week" calendar around all major Indian holidays (Diwali, Holi, Eid, Independence Day) with dedicated restaurant partnerships, themed menus, and targeted campaigns to replicate this effect multiple times per year.

### 8. 🌏 Northeast India Needs a Dedicated Strategy
Sikkim (₹560K), Nagaland (₹576K), and Mizoram (₹824K) are the three lowest-performing states. These are either under-served markets with infrastructure gaps or low-penetration markets with untapped demand. A focused Northeast India playbook — with local cuisine partnerships and regional pricing — could meaningfully move the needle.

---
## Connect With Me

Let's connect, collaborate, or talk data!

- 💼 [LinkedIn](https://www.linkedin.com/in/oluwatofunmi-isholadaniel/)
- 💻 [GitHub](https://github.com/TofunmiTech01)

---

*Built with Microsoft Excel · Analyzed with precision · Designed for decisions.*

