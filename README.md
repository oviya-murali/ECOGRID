# ECOGRID — India Energy Analytics Dashboard

ECOGRID is an interactive Power BI dashboard that analyzes electricity consumption, renewable energy generation, and power plant infrastructure across India. It provides key insights into the country's energy usage, renewable energy trends, and regional consumption patterns, enabling data-driven decision-making through intuitive visualizations.

## Objectives

- To provide a comprehensive view of India's electricity consumption patterns through interactive visualizations.
- To compare energy consumption across different states and identify high-demand regions.
- To analyze renewable energy generation and its contribution to India's energy sector.
- To examine the relationship between energy consumption, renewable generation, and power infrastructure.
- To generate meaningful insights that support sustainable energy planning and development.

## Data Sources

- Kaggle – India Electricity Consumption Dataset
- Kaggle – India Renewable Energy Dataset
- Kaggle – India Power Plants Dataset

## Data Overview

The project combines datasets covering electricity consumption, renewable energy generation, and power plant infrastructure across India.

- Includes state-wise consumption records, renewable energy production, and power plant capacity details.
- Data spans multiple years, enabling trend and comparative analysis.

## Tools Used

- Power Query Editor – Data cleaning, transformation, and handling missing values.
- Data Modelling – Creating relationships between multiple energy datasets.
- DAX Measures – Calculating Total Consumption, Total Capacity, Total Renewable Generation, State Rank, and Energy Gap.
- Interactive Visualizations – Bar charts, line charts, donut charts, maps, and decomposition trees.
- Slicers & Filters – Dynamic state-wise and year-wise analysis.
- Dashboard Design – Creating an intuitive and user-friendly analytical interface.

## Key Insights

- Electricity consumption is concentrated in a few highly industrialized states.
- Renewable energy generation has shown significant growth over recent years.
- Hydro and Wind energy contribute a major share of renewable production.
- A noticeable gap exists between electricity demand and renewable energy generation in several states.

## Dashboard 1 — Electricity Consumption

- KPI Cards – Total States, Total Consumption, Peak Consumption, Lowest Consumption
- State-wise Consumption Analysis – Bar chart comparing electricity consumption across states
- Year-wise Consumption Trend – Line chart showing changes in consumption over time
- Interactive Filtering – State filter for focused analysis

![Electricity Consumption Dashboard](dashboard1.png)

## Dashboard 2 — Renewable Energy

- Renewable Energy Trend – Tracks renewable energy growth over time.
- State-wise Renewable Map – Displays renewable energy distribution across India.
- Interactive Filters – Analyze data by fuel type, state, and year.
- KPI Cards – Show total plants and average capacity per plant.

![Renewable Energy Dashboard](dashboard2.png)

## Dashboard 3 — Consumption vs Renewable Energy

- Consumption vs Renewable Analysis – State-wise comparison of electricity consumption and renewable energy generation.
- Renewable Energy Distribution – Donut chart showing the contribution of different renewable sources.
- Decomposition Tree – Drill-down analysis by zone and state.
- KPI Cards – Total Renewable, Total Capacity, Average Plant Capacity, and Clean Energy Plants.

![Comparison Dashboard](dashboard3.png)
