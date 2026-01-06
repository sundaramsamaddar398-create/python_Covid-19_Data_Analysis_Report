# python_Covid-19_Data_Analysis_Report
This project analyzes COVID-19 data across countries, applying feature engineering to calculate growth rates, trends, and insights. It uses Python, Pandas, NumPy, and Matplotlib to build recruiter-ready visualizations, with insights and dashboards that highlight daily changes and patterns.

# 🌍 Global COVID-19 Data Analysis & Visualization

This project presents an exploratory data analysis (EDA) of the global COVID-19 pandemic using time-series and comparative visualizations. The goal is to uncover trends in case growth, mortality, recovery dynamics, and overall case composition over time using raw, non-aggregated data.

The analysis emphasizes visual storytelling while maintaining transparency around data limitations and filtering choices.

---

## 📊 Key Objectives

- Analyze global COVID-19 trends over time  
- Study relationships between confirmed cases, deaths, recoveries, and growth rates  
- Visualize pandemic progression using multiple chart types  
- Highlight data inconsistencies and reporting limitations  

---

## 🧪 Dataset Overview

- **Source:** Public global COVID-19 dataset  
- **Granularity:** Daily records (no aggregation unless explicitly stated)  
- **Time Period:** January 2020 – April 2022  

### Data Filtering
- Country-level analyses include **only countries with ≥100,000 confirmed cases**
- This filtering improves signal quality and reduces noise from inconsistent reporting

---

## 📈 Visualizations Included 

### Trend & Time-Series Analysis
- Global confirmed cases over time  
- Global deaths and recoveries trends  
- COVID-19 growth rate trend (daily + 7-day moving average)  
- Death–Recovery ratio over time  
- Active vs Closed cases over time  
- COVID-19 case composition (Active, Recovered, Deaths)

### Comparative & Relationship Analysis
- Scatter plots:
  - Confirmed Cases vs Deaths  
  - Confirmed Cases vs Recovered  
  - Active Cases vs Recovery Rate  
  - Active Cases vs Mortality Rate  
- Correlation between **New Deaths vs New Recovered** 

### Smoothing & Stability
- 7-day moving averages applied where appropriate to reduce daily volatility

---

## ⚠️ Important Data Limitations

- **Recovery data was not consistently updated after August 2021**, affecting:
  - Recovery trends
  - Active case calculations
  - Closed case comparisons in later periods
- Sudden drops or plateaus in recovered/closed cases after this date reflect **reporting gaps**, not real-world declines
- Early pandemic growth rates show extreme volatility due to low base counts

These limitations are explicitly acknowledged in the visual interpretations.

---

## 🧠 Key Insights

- Early pandemic phases exhibit sharp growth and volatility, stabilizing over time  
- Growth rates steadily decline as cumulative cases increase  
- Death–Recovery ratios improve significantly after the initial outbreak period  
- Active case surges align with major global waves  
- Correlation between new deaths and new recoveries shows weak-to-moderate association due to reporting delays and regional differences  

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – data manipulation
- **Matplotlib** – data visualization
- **NumPy** – numerical computations

---

## 📌 Conclusion

This project provides a comprehensive visual exploration of the COVID-19 pandemic, balancing raw data analysis with contextual awareness of reporting inconsistencies. While certain metrics become less reliable in later stages due to missing recovery updates, the combined visualizations still offer meaningful insights into global pandemic dynamics.

---

## 📄 License

This project is intended for educational and analytical purposes.  
Feel free to fork, modify, or build upon it.

