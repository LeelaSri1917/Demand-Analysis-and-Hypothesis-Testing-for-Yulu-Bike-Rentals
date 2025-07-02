# Demand-Analysis-and-Hypothesis-Testing-for-Yulu-Bike-Rentals
This project analyzes over 10,000+ bike rental records to understand the impact of weather, season, and working days on rental demand. It includes Exploratory Data Analysis (EDA), Hypothesis Testing (t-test, ANOVA, Chi-Square), and Business Recommendations.
# 🚲 Yulu Bike Rental Demand Analysis

**Author:** Leela Sri Mekala  
**Project Type:** Data Analysis / Demand Forecasting  
**Platform:** Jupyter Notebook / Google Colab  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

---

## 📌 **Objective**

The primary objective of this project is to conduct a **comprehensive demand analysis** for **Yulu**, a micro-mobility service provider. The focus is on understanding user behavior and identifying **key factors affecting demand** using **data analysis** and **statistical techniques**.

---

## 📂 **Dataset Overview**

The dataset contains detailed information related to **Yulu rides**, covering:

- 🕒 **Time Data**: Timestamp of each ride
- 📍 **Location Data**: Station, region, or zone identifiers
- 🌡️ **Weather Conditions**: Temperature, humidity, wind speed, etc.
- 🛴 **Ride Metrics**: Total rides, duration, start and end times
- 📅 **Calendar Info**: Weekday, weekend, holiday

---

## 🔧 **Steps Performed**

### 1. 📥 **Data Preprocessing**
- Converted timestamps to datetime format
- Handled missing and null values
- Standardized categorical fields
- Extracted new date-related features (hour, day, weekday, etc.)

### 2. 📊 **Exploratory Data Analysis (EDA)**
- Analyzed **demand variation** by **hour, day, and month**
- Visualized patterns for **weekday vs weekend**
- Plotted **weather impact** on number of rides
- Identified **high-demand hours and zones**

### 3. 📆 **Feature Engineering**
- Created time-based features: `hour`, `day_of_week`, `month`
- Encoded categorical variables
- Detected trends in usage by **season and holidays**

### 4. 🧪 **Statistical Testing**
- Used **correlation matrix** to find influential variables
- Conducted **hypothesis tests** on:
  - Weather impact on demand
  - Weekend vs weekday usage
  - Hourly vs daily ride trends

---

## 📈 **Key Insights**

- 🔥 **Peak demand** observed between **8 AM – 10 AM** and **5 PM – 8 PM** (commute hours)
- 🏙️ High demand zones include **business districts and metro stations**
- 📉 Rainy and high-humidity days lead to **reduced ride counts**
- 📅 **Weekdays have higher consistent demand**, but weekends show spikes in leisure zones
- ❄️ Demand dips slightly in colder months

---

## ✅ **Business Recommendations**

- 📍 **Increase bike availability** in high-traffic zones during **peak hours**
- 🌧️ Offer discounts or promotions during **bad weather** to sustain ridership
- 📆 Introduce **weekday and weekend-based pricing models**
- 📊 Use insights to plan **fleet redistribution** for improved coverage
- 🧠 Incorporate **real-time weather data** for dynamic demand prediction

---

## 📁 **Project Files**

| File Name                         | Description                                      |
|----------------------------------|--------------------------------------------------|
| `Yulu_Demand_Analysis.ipynb`     | Jupyter/Colab notebook with code and visualizations |
| `README.md`                      | Project overview and key takeaways               |

--
