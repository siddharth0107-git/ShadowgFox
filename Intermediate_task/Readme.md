# 🌆 Delhi Air Quality Index (AQI) Analysis  
### ShadowFox Data Science Internship — Intermediate Task

---

## 🧠 Overview
This project is based on analyzing Delhi’s air quality using real data.  
The main goal is to study how air pollution changes over time, identify which pollutants affect it the most, and understand how seasons impact Delhi’s AQI levels.  

It’s part of my **ShadowFox Data Science Internship (Intermediate Level)** and focuses on data cleaning, visualization, and real-world insight generation using Python.

---

## ⚙️ Tools Used
- **Python** – for coding and analysis  
- **Pandas & NumPy** – for data handling and calculations  
- **Matplotlib & Seaborn** – for visualizing the trends  
- **Jupyter Notebook (Anaconda)** – to run and present the analysis  

---

## 📂 Dataset
**File:** `delhiaqi.csv`  
**Columns:** Date, CO, NO, NO2, O3, SO2, PM2_5, PM10, NH3  
Since there was no direct AQI column, I created one using pollutant data.

---

## 🧮 AQI Calculation
To estimate AQI, I designed a simple formula giving more weight to particulate matter:

\[
AQI = (PM2.5 × 0.45) + (PM10 × 0.35) + (NO2 × 0.08) + (SO2 × 0.07) + (O3 × 0.05)
\]

This helps show how pollution varies by season and source.

---

## 📊 Steps Followed
1. Cleaned and prepared the dataset (renamed columns, converted dates).  
2. Calculated the estimated AQI.  
3. Created new columns like Month and Weekday for deeper insights.  
4. Visualized trends using bar charts, line graphs, boxplots, and heatmaps.  
5. Summarized the main findings and suggestions.

---

## 💡 Key Insights
- Delhi’s **average estimated AQI is around 180**, which falls in the **Poor** category.  
- Pollution is **worst during November–January** due to smog and stubble burning.  
- **PM2.5 and PM10** are the major pollutants affecting Delhi’s air quality.  
- Air quality improves during **July–August** because of monsoon rains.  
- Controlling vehicle emissions and dust can significantly improve the situation.

---

## 🧾 Deliverables
- Jupyter Notebook – `Delhi_AQI_Analysis.ipynb`  
- Dataset – `delhiaqi.csv`  
- Visual Outputs – Trend, Distribution, Boxplot, Heatmap  
- README File – Summary and Explanation  
- GitHub Upload – Under `Intermediate_Task/`  

---

## 🧠 What I Learned
- Handling real-world environmental data  
- Cleaning and transforming datasets  
- Building custom formulas and metrics  
- Visualizing and explaining data clearly  

---

## 👤 Author
**Name:** V. Siddharth  
**Internship:** ShadowFox Data Science  
**Task Level:** Intermediate  
**Month:** November 2025  

---

**This is an original version created with a custom AQI formula, unique charts, and personal insights.**

