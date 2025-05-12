# 💧 Water Quality Portal Data Dashboard

The **Water Quality Portal (WQP) Data Dashboard** is an interactive data visualization project that consolidates and analyzes water quality records from multiple sources across the U.S. With a focus on Kansas, this dashboard empowers policymakers, researchers, and the public with dynamic insights into environmental health, demographic impacts, and spatial trends in water monitoring.

---

## 🌐 Project Overview

This project transforms raw data from the USGS and EPA into intuitive dashboards using Python-based visualizations. It integrates multiple datasets, including chemical concentrations, monitoring stations, and population demographics, to provide a detailed analysis of water quality across Kansas counties.

---

## 📊 Dashboards

### 📍 1. Kansas County Demographics & Environmental Monitoring Dashboard

- Displays population distribution by county.
- Maps 1,000+ monitoring stations (rivers, wells, lakes).
- Highlights drainage area sizes and surface water focus.

![Demographics and Monitoring Dashboard](dashboard_1.png)

---

### 🌡️ 2. Hydro Analytics: Water Quality Metrics and Trends

- Visualizes pH levels over time and by location.
- Shows average population vs. pH level trends.
- Heatmaps to identify spatial clusters of poor or improving water quality.

![Water Quality Metrics and Trends Dashboard](dashboard_2.png)

> Note: You must upload `dashboard_1.png` and `dashboard_2.png` into your GitHub repo to make them visible here.

---

## 📥 Data Sources

- **USGS Water Quality Portal (WQP)**
- **EPA STORET/WQX**
- **USDA STEWARDS**
- Supplemented by:
  - Kansas population data (`Population.xlsx`)
  - Chemical data (`filtered_chemicals1.xlsx`)
  - Monitoring station metadata (`updated_station.xlsx`)

---

## 🔬 Analysis Methods

- Data cleaning and merging with shared identifiers.
- Statistical filtering and outlier detection.
- Use of Pandas, Seaborn, Plotly, and Folium for visual analytics.
- Geospatial trend analysis (by county, by monitoring location).

---

## 🎯 Stakeholder Applications

- **Regulators (EPA, state water boards)**: Ensure policy compliance
- **Scientists & Environmentalists**: Study pollution, trends, ecosystem impact
- **Public Health Officials**: Identify contamination and health risks
- **Educators & Students**: Use real-world data in environmental studies
- **Communities & Advocacy Groups**: Raise awareness, drive action

---

## 🧰 Tools & Technologies

- Python (`pandas`, `matplotlib`, `seaborn`, `plotly`, `folium`)
- Excel for data integration
- PDF report generation
- Jupyter Notebooks


