# 📊 A/B Test Analysis: Facebook vs AdWords Campaigns

This project analyzes the performance of Facebook and AdWords ad campaigns using A/B testing techniques. The goal was to evaluate which platform drove better conversion performance, and whether the observed difference was statistically significant.

---

## 📁 Dataset

- 📄 **A_B_testing_dataset.csv**  
- Fields: `facebook_ad_clicks`, `facebook_ad_conversions`, `adword_ad_clicks`, `adword_ad_conversions`, `date_of_campaign`, and related cost metrics

---

## 🧪 Project Objectives

- Compare Facebook vs AdWords ad performance
- Calculate conversion rates per channel
- Measure uplift % (improvement or decline)
- Perform a Z-test for statistical confidence
- Visualize results in Power BI dashboard

---

## 🔧 Tools Used

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
