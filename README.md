# Climate Risk Dashboard

## Overview

An interactive data visualization dashboard that explores the relationship between temperature change and agricultural production across **184 countries** and **7 staple crops** from **1961–2023**.

The project focuses on identifying potential climate stress patterns using correlation-based analysis and multiple interactive visualizations.

---

## Project Description

This dashboard allows users to analyse how rising temperatures relate to key agricultural metrics:

- Yield (kg/ha)
- Production (tonnes)
- Area Harvested (hectares)

It combines multiple visualizations to present a clear data story on the impact of climate change on food production.

---

## Data Sources

- **FAOSTAT Crops and Livestock Data** (Kaggle)
- **IMF Climate Data Portal**

---

## Dataset Directory

| Dataset | Location |
|----------|----------|
| Raw crop dataset | `data/raw_data_kaggle.csv` |
| Raw temperature dataset | `data/raw_data_imf.csv` |
| Cleaned & merged dataset | `data/Merged_FAOSTAT_Cleaned.csv` |

---

## Features

### Interactive Controls

- Select agricultural metric:
  - Yield
  - Production
  - Area Harvested
- Adjustable year range (1961–2023)
- Multi-selection of countries
- Multi-selection of crops
- Reset functionality for quick analysis

### Visualizations

#### Temperature Trend Map
Displays global temperature anomalies over time.

#### Crop Trend Line Chart
Shows agricultural trends across selected years.

#### Climate Risk Map
Highlights regions with potential climate-related risks.

#### Country Ranking Bar Chart
Ranks countries based on the selected metric.

#### Correlation Heat Map
Displays country–crop level correlations between temperature change and the selected agricultural metric.

The colour scale ranges from **-1 to 1**, representing the strength and direction of the relationship.

---

## Key Insight

Global agricultural trends may appear relatively stable due to technological advancements such as improved seeds, fertilizers, and irrigation.

This dashboard focuses on **country–crop level analysis**, helping reveal uneven climate impacts and identify regions that may be more vulnerable to climate change.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- D3.js (v7)
- TopoJSON

---

## Project Structure

```text
├── index.html                  # Main dashboard layout
├── main.js                     # Data processing and visualizations
├── main.css                    # Styling
├── d3.v7.min.js                # D3.js library
└── data/
    ├── raw_data_kaggle.csv
    ├── raw_data_imf.csv
    └── Merged_FAOSTAT_Cleaned.csv
```

---

## How to Run

1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. Use the interactive controls to explore the dashboard.

> **Note:** No server setup is required.
