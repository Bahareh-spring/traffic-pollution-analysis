# 🚦🌫️ Traffic Accidents and Air Pollution Analysis

This project explores the relationship between traffic accident counts and urban air pollution levels across major US cities. Using real-world datasets, we attempt to uncover whether higher traffic congestion correlates with worse air quality.

---

## 📚 Datasets

- **US Traffic Accidents Dataset:** [Kaggle Link](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **US Air Pollution Dataset:** [Kaggle Link](https://www.kaggle.com/datasets/sogun3/uspollution)

---

## 🎯 Project Objectives

- Merge traffic and air pollution datasets based on **City** and **Date**.
- Analyze the **relationship** between accident counts and various **pollutant AQI levels** (Ozone, NO2, CO, SO2).
- Perform **city-level correlation analysis** to detect localized patterns.
- Visualize findings using **Python** and **Power BI** (dashboard coming soon).

---

## 🛠️ Tools and Technologies

- **Python:** pandas, matplotlib, seaborn
- **Power BI:** (Dashboard in progress)
- **GitHub:** Project documentation and version control

---

## 🧹 Data Cleaning and Preparation

- Extracted `Date` from accident timestamps.
- Grouped traffic data by `City` and `Date`.
- Merged datasets on `City` and `Date`.
- Removed unnecessary columns and handled missing values.

---

## 📊 Exploratory Data Analysis (EDA)

- Scatter plots between **Accident Count** and **Ozone/NO2/CO/SO2 AQI** levels.
- Time series analysis of **daily accident counts** and **pollution trends**.
- **Correlation heatmaps** to understand relationships between variables.

---

## 🏙️ City-Level Correlation Analysis

| City | Average Correlation (Accidents vs Pollution) |
|------|----------------------------------------------|
| Memphis | -0.111 |
| Grand Rapids | -0.090 |
| Tulsa | 0.081 |
| Houston | 0.072 |
| (others...) | ... |

- Most cities showed **weak correlation** between traffic accidents and pollution levels.
- Some cities (e.g., **Houston**, **Tulsa**) exhibited slight positive correlations.

---

## 📈 Key Visualizations

- **Heatmap:** Correlation between accident counts and pollution levels.
- **Scatter Plots:** Accident counts vs various pollutant AQIs.
- **Line Graphs:** Trends of traffic accidents and air pollution over time.
- **City-specific Analysis:** Focused on Houston and Tulsa.

---

## 🧠 Insights and Conclusions

- **Traffic accidents alone do not strongly correlate** with air pollution levels in most cities.
- Other factors such as **industrial emissions**, **weather**, and **urban layout** likely play significant roles.
- **Real-world data** often presents complex, non-linear relationships.

---

## 🚀 Future Improvements

- Incorporate **weather data** (temperature, humidity, wind) into the model.
- Perform **multi-variable regression analysis** to better understand pollution predictors.
- Extend the study to **seasonal trends** and **weekend vs weekday** patterns.

---

## 📂 Project Structure
