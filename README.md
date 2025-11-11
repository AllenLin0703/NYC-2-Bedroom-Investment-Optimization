## 📘 Project Overview
This project focuses on analyzing **New York City Airbnb listings** to evaluate investment potential for **2-bedroom properties**.  
By comparing annual rental income, cleaning fees, and property prices across different neighborhoods, the analysis identifies ZIP codes with the **best payback performance** for real estate investment.
> 中文简介：  
> 本项目通过对纽约市 Airbnb 房源数据进行探索性分析，计算房源的年收益与投资回报周期，并比较不同区域（Zipcode）的表现，从而找出最具投资价值的区域。
---

## 📊 Analysis Process

### 1️⃣ Data Cleaning
- Removed missing or invalid values (price, reviews, location).  
- Focused on listings with **2 bedrooms** for consistency.  
- Standardized price columns by removing "$" and commas.

### 2️⃣ Key Metrics
We calculated **annual revenue** and **payback ratio** using the following logic:
```text
Final Revenue = Base price + Extra guest fee + Cleaning fee + Security deposit
Payback Ratio = Final Revenue / Property Price

### 3️⃣ Exploratory Data Analysis (EDA)
- Compared **average payback rates** across NYC boroughs.  
- Found **Kings County (Brooklyn)** shows high growth and moderate price.  
- Identified stable upward trends in specific ZIP codes.

---

## 📈 Visualization Highlights
- Payback distribution by borough  
- Price vs Payback correlation heatmap  
- Top-10 ZIP code ROI comparison  
- Interactive map with investment clusters (Folium)

---

## 🧠 Key Insights
**Why NYC?**
1. High growth potential  
2. Stable housing trend  

**Why Kings County?**
1. Rapid growth rate  
2. High short-term volatility  
3. Moderate price suitable for mid-term investment

---
✨ *This project demonstrates how data-driven methods can guide smarter real estate investment decisions in the NYC short-term rental market.*
