# 🚦 US Traffic Accident Data Visualization (2016–2023)

This project presents a comprehensive **data visualization and analysis** of over 7.7 million US traffic accidents from 2016 to 2023. Using temporal, geographical, and environmental attributes, we explore patterns in accident frequency, severity, and location. The goal is to uncover actionable insights that can assist **urban planners, policymakers, and transportation agencies** in improving road safety.

---

## 🧾 Dataset

**Source:** [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
**Size:** 7.7 million records  
**Time Range:** 2016–2023  
**Columns Used:**
- ID, Severity, Start_Time, End_Time  
- Start_Lat, Start_Lng, City, County, State  
- Wind_Speed (mph), Weather_Condition

---

## 📊 Visual Analyses Included

- 📅 **Temporal Trends**  
  - Yearly, monthly, and daily line charts  
- ⏰ **Heatmaps**  
  - Hour of day vs day of week accident frequency  
- 🌎 **Geospatial Heatmaps**  
  - Accident hotspots by city and state using hexbin and bubble maps  
- 🌦️ **Weather Analysis**  
  - Boxplots of severity by weather condition  
  - Top weather types by accident volume  
- 📈 **Seasonal Decomposition**  
  - Monthly trend + seasonality + residuals  
- 🧭 **Interactive Dashboard (4 tabs)**  
  - Overview  
  - By State  
  - By Time  
  - Severity Analysis

---

## 🛠️ Preprocessing & Feature Engineering

- Selected only relevant columns from the full dataset  
- Cleaned and standardized timestamp fields  
- Extracted `year`, `month`, `day` from datetime for trend analysis  
- Filtered inconsistent or missing records  
- Grouped and aggregated data for city/state/time-level visualizations

---

## 🧠 Key Insights

- **Peak accident hours**: 7–9 AM and 4–6 PM on weekdays  
- **Most dangerous states**: California, Florida, Texas  
- **Safest states**: Vermont, South Dakota, Maine  
- **Most dangerous cities**: Los Angeles, Houston, Dallas  
- **High-risk weather**: Even “Fair” weather has many accidents, followed by “Cloudy” and “Rain”  
- **Winter months** show higher frequency — likely due to weather and holidays

---

## 🧩 Tools Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `folium`, `dash`  
- Jupyter Notebook  
- Kaggle dataset integration  
- Plotly Dash for dashboard interactivity

---

## 📎 References

- [US Accidents – Kaggle Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
