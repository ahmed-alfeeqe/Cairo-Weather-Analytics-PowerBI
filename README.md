# Cairo Weather & Climate Analytics Dashboard

A meteorological Business Intelligence dashboard built with Microsoft Power BI to analyze historical climate observations, seasonal patterns, and weather dynamics for Cairo, Egypt.

---

## Overview
This project analyzes multi-year daily weather records for Cairo to evaluate:
- Long-term temperature fluctuations and apparent ("feels-like") temperature variances.
- Rainfall volumes, frequency of precipitation days, and relative humidity trends.
- Wind velocity patterns, peak gusts, and their correlation with atmospheric pressure.

---

## Dataset
The analysis is based on `Cairo-Weather.xlsx`, capturing daily weather parameters:
- Temperature: Maximum, mean, and minimum temperatures (`temperature_2m_*`).
- Apparent Temperature: Heat index and wind chill adjustments (`apparent_temperature_*`).
- Precipitation: Daily precipitation sum, rain sum, and precipitation hours.
- Wind & Atmosphere: Maximum wind speed, peak gusts, wind direction, and relative humidity.

---

## Report Structure
- Main Navigation: Central hub connecting all analysis pages.
- Temperature Dynamics: Area charts tracking temperature ranges across months and seasons.
- Precipitation & Humidity: Column and line charts displaying rainfall accumulation and humidity levels.
- Wind & Atmospheric Pressure: Scatter plots evaluating the relationship between wind speed and barometric pressure.

---

## Tech Stack
- Microsoft Power BI Desktop
- Microsoft Excel (`Cairo-Weather.xlsx`)
- Power Query (ETL)
- DAX

---

## Usage Instructions
1. Install Microsoft Power BI Desktop.
2. Clone or download this repository.
3. Open `Cairo_Weather_Dashboard.pbix` in Power BI Desktop to view the report and underlying data model.
