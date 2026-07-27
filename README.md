# rio-airbnb-analytics
Data analysis and Power BI dashboard for Rio de Janeiro Airbnb market trends
# 📊 Rio de Janeiro Airbnb Market & Seasonality Analysis

## About the Project

This end-to-end data analytics project explores Airbnb market trends in Rio de Janeiro using the most recent 12-month dataset publicly available from [Inside Airbnb](http://insideairbnb.com/). The primary objective was to identify seasonal demand patterns, occupancy behavior, and pricing differences across neighborhoods while building a complete analytics workflow from SQL data preparation to interactive Power BI dashboards. The project demonstrates practical skills in SQL, data modeling, business intelligence, and data storytelling.

---

## Dashboard Preview

![Power BI Dashboard Preview](dashboard-preview.png)

---

## Tech Stack & Skills Demonstrated

**Data Engineering (Google BigQuery / SQL)**
* Extraction and transformation of raw Airbnb listings and calendar datasets.
* Performed joins across multiple tables to create an analytical data model.
* Removal of outliers and standardization of records.
* Calculated median booked prices and monthly occupancy metrics.
* Development of reusable SQL queries for reporting purposes.

**Business Intelligence**
* Power BI Desktop.
* Development of interactive dashboards.
* Creation of DAX measures for Occupancy Rate, Median Booked Price, and Average Daily Rate (ADR).

**Data Visualization**
* Clean dashboard layout.
* Business-focused key performance indicators.
* Time-series analysis.
* Neighborhood comparison.
* English localization.

---

## Key Insights

**Premium Neighborhoods Lead Prices**
High-end regions such as Joá and Itanhangá recorded the highest Average Daily Rates during the analyzed period, considerably outperforming the city average. This behavior points to strong pricing power associated with exclusive properties and lower accommodation supply in these locations.

**High-End Areas Outperform Traditional Tourist Districts**
Although Copacabana is one of the most famous tourist destinations in Rio de Janeiro, its Average Daily Rate stayed below several high-end residential neighborhoods. This dynamic may reflect a higher concentration of listings and fiercer price competition in areas with high tourist supply density.

**Peak Occupancy Outside the Carnival Season**
Based on the last 12 months of available data, the occupancy rate reached its highest levels during April and May, surpassing the months traditionally associated with Carnival tourism. This suggests that demand remained strong during the shoulder season throughout the analyzed period.

**Price Stability Throughout the Year**
Median booked prices remained relatively stable across the studied months despite noticeable variations in occupancy. The results point to consistent pricing behavior by hosts in the recent period.

---

## Repository Structure

```text
├── 01_bairros_precos.csv          # Neighborhood pricing dataset
├── 02_sazonalidade_completa.csv   # Monthly occupancy and pricing dataset
├── rio_airbnb_dashboard.pbix      # Power BI dashboard file
└── dashboard-preview.png          # Dashboard preview image

```

---

## Dashboard Highlights

The dashboard enables users to:

* Analyze monthly occupancy trends.
* Compare daily rates among neighborhoods.
* Track the evolution of median booked prices over time.
* Identify seasonal demand patterns.
* Explore the short-term rental market of Rio de Janeiro through interactive visualizations.

---

## Skills Demonstrated

* SQL (Google BigQuery)
* Power BI
* DAX
* Data Cleaning
* Data Modeling
* Business Intelligence
* Data Visualization
* Data Storytelling

---

## Author

**Igor Antunes**  
*Data Analyst | SQL • Python • Power BI • Tableau*  
[LinkedIn Profile](https://www.linkedin.com/in/igor-antunesc/) | [GitHub Portfolio](https://github.com/igor-antunesc)
