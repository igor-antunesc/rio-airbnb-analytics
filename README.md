# rio-airbnb-analytics
Data analysis and Power BI dashboard for Rio de Janeiro Airbnb market trends
# 📊 Rio de Janeiro Airbnb Market & Seasonality Analysis

## About the Project & Motivation
As someone based in Brazil, I've always been fascinated by how tourism surges impact our major economic hubs. For this project, I wanted to dive deep into the short-term rental market in **Rio de Janeiro**—one of Latin America's top travel destinations. 

Using **Google BigQuery (SQL)** for data engineering and **Power BI** for visualization, this end-to-end analytics project uncovers real-world market dynamics, focusing on monthly seasonality, occupancy fluctuations, and average daily rates (ADR) across different neighborhoods.

---

## 📈 Dashboard Preview
![Power BI Dashboard Preview](dashboard-preview.png)

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Data Extraction & Transformation (SQL / Google BigQuery):** Queried raw datasets, handled outliers, calculated medians, performed `JOINs` between listings and calendar tables, and standardized data structures to prepare a clean data model.
* **Business Intelligence & Visualization:** Power BI Desktop.
* **Data Modeling & DAX:** Created clean, localized aggregation measures (`AVERAGE`) for metrics like Occupancy Rate, Median Booked Price, and Average Daily Rate (ADR).
* **Data Visualization & UX:** Applied professional formatting principles, high-contrast typography, custom card effects, and internationalized localization (English UI/UX).

---

## 📊 Key Insights & Findings
1. **Premium Neighborhoods Lead Pricing:** High-end coastal and luxury regions like **Joá** and **Itanhangá** command the highest Average Daily Rates (ADR), significantly outperforming the city baseline due to exclusive properties and high-demand tourism profiles.
2. **The Copacabana Anomaly:** Surprisingly, **Copacabana**—Rio's most iconic global postcard and high-density tourist hub—did not make the top 15 list of neighborhood pricing metrics analyzed in this specific scope, highlighting a fascinating concentration effect in other micro-regions.
3. **Counter-Intuitive Seasonality Peak:** While Rio de Janeiro's famous Carnival drives massive tourism spikes in February and March, the data reveals that actual occupancy and stay peaks occur later in **April and May**, pointing to extended shoulder-season preferences or remote work tourism trends.
4. **Micro-Price Fluctuations:** The analysis uncovered striking stability and minute, cent-level price variations across baseline bookings, proving a high degree of automated or rigid pricing strategies among hosts during specific periods.

---

## 📂 Repository Structure
```text
├── 01_bairros_precos.csv          # Neighborhood pricing dataset
├── 02_sazonalidade_completa.csv   # Seasonality and occupancy dataset
├── rio_airbnb_dashboard.pbix      # Power BI source file
└── dashboard-preview.png          # Dashboard screenshot
```
---

---

## Author
**Igor Antunes**  
*Transitioning Data Analyst | SQL, Python, Power BI, Tableau*  
[LinkedIn Profile](https://www.linkedin.com/in/igor-antunesc/) | [GitHub Portfolio](https://github.com/igor-antunesc)
