# 📊 A/B Test Analysis: Facebook vs AdWords Campaigns

This project analyzes the performance of Facebook and AdWords ad campaigns using A/B testing techniques. The goal was to evaluate which platform drove better conversion performance, and whether the observed difference was statistically significant.

---

## 🧪 Project Objectives

- Compare Facebook vs AdWords ad performance
- Calculate conversion rates per channel
- Measure uplift % (improvement or decline)
- Perform a Z-test for statistical confidence
- Visualize results in Power BI dashboard

---

## 🔧 Tools and Technique Used

- PostgreSQL (Data processing + uplift and Z-test calculations)
- Power BI (Data visualization & dashboard creation)
- SQL (for metric calculation & statistical testing)

---

## 📌 Key Metrics

| Metric | Value |
|--------|--------|
| 📈 Uplift % | **-63.58%** *(AdWords underperformed vs Facebook)* |
| 📉 Z-Score | **-72.91** |
| 🧠 P-Value | **2.00** *(Statistically significant)* |
| ✅ Facebook Conv Rate | **27%** |
| ❌ AdWords Conv Rate | **10%** |

---

## 📊 Dashboard Highlights

- 📆 Time-series chart of uplift % trend
- 📊 Bar and area charts of conversions/clicks by year
- 🔢 KPI cards showing Z-score, p-values, and conversion rates
- 🎯 Campaign count metrics for both platforms

## 🧠 Insights

> Facebook outperformed AdWords by 63.58% in conversion efficiency. The difference is statistically significant (z = -72.91), indicating Facebook is the stronger performer in this A/B test.
