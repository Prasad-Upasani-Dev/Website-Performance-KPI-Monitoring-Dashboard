# Website Performance & KPI Monitoring Dashboard — Tableau

## Overview

A Tableau-based analytics dashboard built to give businesses a comprehensive view of website performance across traffic, engagement, conversions, and revenue. The dashboard supports data-driven decision-making by surfacing SEO effectiveness, marketing channel performance, and audience behavior — with built-in period-over-period comparisons for trend analysis.

---

## Dashboard Features

### Website Traffic Analysis
- Total sessions and engagement trend tracking
- Current vs. previous period performance comparison
- Traffic breakdown by region and country

### User Behavior Insights
- Bounce rate trends and comparative analysis
- Transaction volume and sales performance monitoring
- Conversion rate tracking over time

### Revenue & Financial Performance
- Total revenue generated and historical trend visualization
- Revenue comparison against prior periods
- Top revenue-driving keywords displayed via word cloud

### Marketing & Acquisition Performance
- Traffic channel and source attribution
- Keyword performance and SEO ranking analysis
- New vs. returning visitor segmentation

### Demographic & Geographic Analysis
- Gender-based KPI breakdown via donut chart
- Age group segmentation and performance trends
- Global KPI distribution via geospatial map

---

## Data Sources

All datasets are sourced from **Google Analytics** exports:

| Dataset | Description |
|---|---|
| ga_data_by_geography | Sessions, traffic, and user behavior by location |
| ga_data_by_keywords | Keyword rankings and SEO performance metrics |
| ga_data_by_channel_and_source | Marketing channel and traffic source attribution |
| ga_data_by_user_type | New vs. returning visitor segmentation |
| ga_data_by_gender | Gender-based engagement and conversion data |
| ga_data_by_age | Age group segmentation and performance trends |

---

## Data Processing & Modeling

- Implemented **custom date range filters** for flexible period-based analysis
- Built **KPI selection parameters** enabling dynamic, real-time metric switching
- Developed **relational models** connecting traffic sources, engagement, and revenue data
- Constructed **period-over-period comparison logic** for trend benchmarking

---

## Reference Documents

- [Dashboard Instructions](Custom_Dashboard%202%20instructions.pdf)
