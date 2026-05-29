# 🛍️ Shopify Trending Products & Social Media Sales Analytics

## 📌 Project Overview
This project performs an end-to-end Data Analytics on **Shopify's Trending Products Dataset**. The core objective is to analyze which product categories drive the highest revenue, evaluate the market share of different trend sources (Amazon, Instagram, TikTok, etc.), and find the correlation between social media hype (Trend Score) and actual business revenue.

## 🛠️ Tech Stack Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

## 📊 Key Data Insights

### 1. Trend Source Share (Revenue Breakdown)
Discovered that **Amazon Best Sellers (26.9%)** and **Instagram Shop (25.5%)** are the biggest revenue drivers, whereas **TikTok Shop Viral** only contributes **1.6%** to long-term revenue.

### 2. Hype vs Revenue (The 90+ Rule)
Proven through scatter plot analysis that a product needs a **Trend Score of 90+** to experience exponential revenue growth. Scores below 90 generate flat/average sales.

### 3. Feature Correlation Matrix
Evaluated the relationship between Units Sold, Estimated Revenue, and Trend Score. Confirmed a moderate relationship (0.56) between quantities and revenue due to product pricing variations.

## 🎯 Strategic Business Recommendations
1. **Focus on Amazon & Instagram:** Businesses should allocate 80% of their ad budget to Amazon SEO and Instagram Shop integration.
2. **The 90+ Trend Rule:** Do not over-invest in products unless their trend score crosses 90, as low-tier viral trends don't guarantee massive conversions.
