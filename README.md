# 🚗 Car Price Analysis — Exploratory Data Analysis & Insights

## 📄 Overview
This project explores a dataset of over **550,000 used car sales** in North America, analyzing how **vehicle attributes, regional factors, and market segments** influence resale prices.  
The analysis provides actionable insights for inventory sourcing, pricing strategies, and targeted marketing.

---

## 🔍 Objectives
- Identify key vehicle attributes impacting resale value
- Analyze regional differences and price volatility
- Pinpoint optimal vehicle age and mileage thresholds for value retention
- Assess transmission type and condition effects
- Deliver clear, data-driven recommendations

---

## 📊 Dataset
- **Rows:** 558,837
- **Columns:** 16
- Includes:  
  `year`, `make`, `model`, `trim`, `body`, `transmission`, `vin`, `state`, `condition`, `odometer`, `color`, `interior`, `seller`, `mmr`, `sellingprice`, `saledate`

---

## 📈 Key Insights

### 🚘 Vehicle Attributes & Selling Price
- Luxury brands (Rolls-Royce, Ferrari, Lamborghini) and niche body styles (convertibles, specialty coupes) command the highest premiums.
- Cars aged **3–5 years**, with mileage under **50k–100k miles**, retain more value.

### 🌎 Regional Price Differences
- Highest average resale prices: Ontario (\$17.8k), Tennessee (\$17k)
- Lowest: New Mexico (\$6.2k), Massachusetts (\$6.7k)

### 🕒 Optimal Age & Mileage
- Depreciation steepest in the first **3 years**.
- Price cliffs beyond **50k** and **100k miles**.

### ⚙️ Transmission & Condition
- Automatic vehicles sell for significantly more (\$12.1k) than manual (\$8.6k), confirmed statistically (p < 0.0001).
- Higher condition scores correlate with higher prices.

### 📊 Price Volatility
- Most volatile states: QC, AB, UT — wide price ranges.
- Least volatile: NS, OK — uniform markets.

---

## 🧰 Tools & Libraries
- Python 3.11
- pandas, numpy
- seaborn, matplotlib
- scipy (T-tests)

---
## 📄 Next Steps
- Build an interactive dashboard (Tableau/PowerBI)
- Train a predictive model for price estimation
- Extend analysis to additional features like color, interior, trim

---

## ✍️ Author
**Ibrahima Ball**  
📧 [ball.ibrah@gmail.com](mailto:ball.ibrah@gmail.com)

