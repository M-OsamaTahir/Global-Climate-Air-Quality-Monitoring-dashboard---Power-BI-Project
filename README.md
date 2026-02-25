# 🌍 Global Climate & Air Quality Monitoring Dashboard

> An interactive Power BI dashboard tracking global temperature, air pollution, ozone levels, and particulate matter across regions and cities from 2024 to 2026.

---

## 🔍 Overview

This dashboard provides a unified view of global climate conditions and air quality metrics. It enables environmental analysts, researchers, and policymakers to monitor real-time and historical trends in temperature, humidity, wind speed, and key air pollutants — filterable by year, month, season, and region.

---

## 📌 Key Metrics (All-Time Averages)

| Metric | Value |
|---|---|
| 🌡️ Avg Temperature | 21.58 °C |
| 🤔 Avg Feels Like Temperature | 22.47 °C |
| 💧 Avg Humidity | 66.16% |
| 💨 Avg Wind Speed | 12.99 Kph |

---

## 📊 Dashboard Sections

### 1. Average Temperature: Actual vs. Feels Like
A dual-line chart comparing **actual recorded temperature** against **perceived (feels like) temperature** from April 2024 to January 2026. The two lines track closely, with peak values around July 2025 (~25.9°C actual, ~24.5°C feels like) and a gradual decline into early 2026.

### 2. Air Pollution Dynamics Over Time
A time series area chart tracking **NO₂ (%)** and **SO₂ (%)** concentrations from April 2024 to January 2026. NO₂ levels climbed significantly through mid-2025, peaking at ~20.8%, before stabilizing. SO₂ shows a steadier, lower trend throughout the period.

### 3. Average Ozone (µg/m³) Trends Over Time
A high-frequency line chart showing **ozone concentration** fluctuations from July 2024 to January 2026. Ozone levels were most volatile in mid-2024 (spikes near 80 µg/m³) and gradually stabilized into a lower, steadier range by 2026.

### 4. Average CO Concentration (ppm) by Region
A bar chart ranking regions by **carbon monoxide levels**:
- 🏆 **Asia** — 0.74 ppm (highest)
- **Americas** — 0.42 ppm
- **Africa** — 0.33 ppm
- **Europe, Atlantic, Indian Ocean, Australia, Pacific** — range from 0.14–0.27 ppm

### 5. PM10 & PM2.5 Levels Across Regions (µg/m³)
A combined bar + line chart comparing **coarse (PM10)** and **fine (PM2.5)** particulate matter across regions:
- **Asia** leads at 94 µg/m³ PM10 and 64 µg/m³ PM2.5 — well above WHO guidelines
- **Africa** and **Atlantic** follow at 46 and 24 respectively
- **Australia** records the cleanest air at 9 µg/m³

### 6. Top 10 Cities by Highest Average Temperature (°C)
A stepped line chart of the hottest cities globally:
- 🏆 **Ar Riyadh** — ~44°C (hottest)
- **Kuwait, Morocco City, Krasnoy Turkmenistan, Abu Dhabi, Doha** in the 35–40°C range
- **Djibouti, Khartoum, Kuwait City, Muscat** closing the top 10 at ~30°C

### 7. Temperature–Humidity Correlation Across Global Cities
A scatter plot exploring the relationship between **average humidity (%)** and **average temperature (°C)** across hundreds of global cities. The plot reveals a wide spread — high humidity cities tend to cluster in the 15–30°C range, while the hottest cities (40°C+) appear at lower humidity levels.

---

## 🗂️ Dataset

This dashboard is built on global climate and air quality data covering **2024–2026**, filterable by:

| Dimension | Options |
|---|---|
| **Year** | 2024, 2025, 2026 |
| **Month(s)** | All / Individual months |
| **Season(s)** | All / Spring, Summer, Autumn, Winter |
| **Region(s)** | All / Asia, Africa, Americas, Europe, etc. |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **DAX** | KPI calculations, MoM/YoY comparisons |
| **Power Query (M)** | Data transformation & cleaning |

---

## 💡 Key Insights

- **Asia dominates air pollution metrics** — highest CO (0.74 ppm), PM10 (94 µg/m³), and PM2.5 (64 µg/m³), pointing to significant industrial and urban emission levels.
- **NO₂ levels surged through 2025** before stabilizing, suggesting a temporary spike in vehicular or industrial activity.
- **Ar Riyadh is the hottest city** in the dataset at ~44°C average, followed closely by Kuwait and Moroccan cities.
- **Australia and the Pacific** record the cleanest air quality globally, with PM10 values as low as 9 µg/m³.
- **Temperature and humidity share an inverse relationship** at extremes — the hottest cities tend to be drier, while humid cities cluster in moderate temperature bands.
- **Ozone volatility in mid-2024** warrants further investigation into seasonal or industrial triggers.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Global meteorological and air quality data sources
- Microsoft Power BI for the visualization platform
- WHO Air Quality Guidelines for benchmark reference

---

*Built with ❤️ for climate awareness and environmental data storytelling.*
