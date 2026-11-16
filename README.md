# 🌦️ Cairo Weather & Climate Analytics Dashboard (Power BI)

An interactive, multi-page meteorological Business Intelligence dashboard built with **Microsoft Power BI** to analyze historical climate trends, seasonal variations, and weather dynamics for Cairo, Egypt.

---

## 📌 Executive Summary & Project Purpose
Weather and climate patterns directly influence urban planning, energy consumption, agriculture, and daily public life. This project provides a comprehensive analytical view of Cairo's weather telemetry, uncovering:
- Long-term temperature fluctuations and "feels-like" (apparent) temperature discrepancies.
- Rainfall patterns, rainy day distributions, and relative humidity trends across seasons.
- Wind velocity, extreme gusts, and their correlation with barometric pressure changes.

---

## 📊 Dataset & Variables Overview
The underlying dataset (`Cairo-Weather.xlsx`) captures daily historical weather observations with granular metrics:

| Metric Category | Telemetry & Variables Included |
| :--- | :--- |
| **Temperature** | `temperature_2m_max`, `temperature_2m_mean`, `temperature_2m_min` |
| **Apparent Temp** | `apparent_temperature_mean`, `apparent_temperature_max`, `apparent_temperature_min` |
| **Precipitation** | `precipitation_sum`, `rain_sum`, `precipitation_hours`, `weather_code` |
| **Wind & Air** | `wind_speed_10m_max`, `wind_gusts_10m_max`, `wind_direction_10m_dominant` |
| **Atmosphere & Sun**| `relative_humidity_2m_mean`, `daylight_duration`, `sunshine_duration`, `shortwave_radiation_sum` |

---

## 🖥️ Dashboard Architecture & Pages Tour

### 1. 🏠 Navigation Hub (`Main page`)
* Clean modern landing interface designed with custom vector layouts and intuitive navigation buttons directing users to each analytical deep-dive.

### 2. 🌡️ Temperature Dynamics (`Temp`)
* **KPI Metrics**: Real-time summary cards displaying Average Temp, Absolute Highs, and Record Lows.
* **Area Trend Visuals**: Multi-layered area charts mapping daily and monthly temperature bandwidths (Min vs. Mean vs. Max).
* **Interactive Slicers**: Dynamic date and seasonal timeline filtering.

### 3. 🌧️ Rainfall & Humidity Analysis (`Rain & Humidity`)
* **Precipitation Breakdown**: Clustered column & line charts showing rainfall volume distribution and rainy day frequency.
* **Humidity Spectrum**: Tracking relative humidity percentages across dry and humid periods of the year.
* **Seasonal Slicers**: Multi-dimensional filtering to isolate specific weather events.

### 4. 💨 Wind Velocity & Atmospheric Pressure (`Wind & Pressure`)
* **Wind Metrics**: Gauge and card visuals for sustained maximum wind speeds and peak gust intensity.
* **Correlation Scatter Plot**: Correlation analysis between wind speed fluctuations and atmospheric barometric pressure shifts.
* **Trend Analysis**: Line charts tracking seasonal wind patterns and dominant air currents.

---

## 🎨 UI/UX & Visual Design
- **Custom Design Themes**: Styled using custom Power BI JSON themes (`Power_BI_Theme.json`) for consistent typography and contrast.
- **Custom SVG Layouts**: Integrated modular SVG background containers (`boxy-sections.svg`, `clean-rounded-1.svg`, `clean-roudned-9.svg`) for clean aesthetic card separation.
- **Visual Iconography**: High-quality weather indicators (`heavy-rain.png`, `temprature.png`, `wind.png`).

---

## 🛠️ Tech Stack & Skills
- **BI Tool:** Microsoft Power BI Desktop
- **Data Transformation & Modeling:** Power Query (ETL), DAX Measures
- **Data Source:** Microsoft Excel (`Cairo-Weather.xlsx`)
- **Graphic Assets:** Custom SVGs & Figma / JSON Theme styling

---

## 🚀 How to Run the Project
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Clone or download this repository:
   ```bash
   git clone https://github.com/ahmed-alfeeqe/Cairo-Weather-Analytics-PowerBI.git
   ```
3. Open `Cairo_Weather_Dashboard.pbix` in Power BI Desktop.
4. (Optional) Inspect or update raw data inside `Cairo-Weather.xlsx`.

---

## 👤 Author
**Ahmed Alfeeqe** — Data Analysis Portfolio Project
