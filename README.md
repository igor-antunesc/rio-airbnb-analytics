# rio-airbnb-analytics
Data analysis and Power BI dashboard for Rio de Janeiro Airbnb market trends
# 📊 Rio de Janeiro Airbnb Market & Seasonality Analysis

## 🇧🇷 About the Project & Motivation
As someone based in Brazil, I've always been fascinated by how tourism surges impact our major economic hubs. For this project, I wanted to dive deep into the short-term rental market in **Rio de Janeiro**—one of Latin America's top travel destinations. 

Using Power BI, I built this dashboard to uncover real-world market dynamics, focusing on monthly seasonality, occupancy fluctuations, and average daily rates (ADR) across different neighborhoods.

---

## 📈 Dashboard Preview
![Power BI Dashboard Preview](dashboard-preview.png)

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Tool:** Power BI Desktop
* **Data Transformation & Modeling:** Data cleaning, custom schema structures, and measure development.
* **DAX (Data Analysis Expressions):** Created clean, localized aggregation measures (`AVERAGE`) for metrics like Occupancy Rate, Median Booked Price, and Average Daily Rate.
* **Data Visualization & UX:** Applied professional formatting principles, high-contrast typography, custom card effects, and internationalized localization (English UI/UX).

---

## 📊 Key Insights & Findings
1. **Premium Neighborhoods Lead Pricing:** High-end coastal and luxury regions like **Joá** and **Itanhangá** command the highest Average Daily Rates (ADR), significantly outperforming the city baseline due to exclusive properties and high-demand tourism profiles.
2. **Seasonality & Occupancy Patterns:** The occupancy rate exhibits sharp seasonal shifts throughout the year, reflecting peak holiday tourism periods versus low seasons in Rio de Janeiro's calendar.
3. **Pricing Stability vs. Demand:** While median booking prices remain relatively steady across certain baseline periods, occupancy rates fluctuate heavily, highlighting optimal windows for dynamic pricing strategies.

---

## 📂 Repository Structure
```text
├── 01_bairros_precos.csv          # Neighborhood pricing dataset
├── 02_sazonalidade_completa.csv   # Seasonality and occupancy dataset
├── rio_airbnb_dashboard.pbix      # Power BI source file
└── dashboard-preview.png          # Dashboard screenshot
