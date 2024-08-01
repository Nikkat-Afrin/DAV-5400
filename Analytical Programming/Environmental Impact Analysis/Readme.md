# Project Title: Environmental Impact Analysis Through Data Science

## Introduction

The increasing levels of carbon dioxide (CO2) over the past few decades have led to significant environmental changes, including global warming, rising sea levels, and more frequent natural disasters. This project aims to explore the correlation between CO2 concentrations, surface temperature rise, sea level changes, and the frequency of natural disasters over the past 30 years.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Acquisition](#data-acquisition)
3. [Data Jargon](#data-jargon)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Data Preparation and Feature Engineering](#data-preparation-and-feature-engineering)
6. [Research Analysis](#research-analysis)
7. [Conclusion](#conclusion)
8. [Project Structure](#project-structure)
9. [How to Use](#how-to-use)
10. [Acknowledgements](#acknowledgements)

## Data Acquisition

For this project, data was collected from the IMF Climate Change Data site, which includes:

1. **Annual Surface Temperature Change**:
   - Format: CSV
   - Source: [IMF Climate Change Data](https://climatedata.imf.org/datasets/4063314923d74187be9596f10d034914/explore)

2. **World Monthly Atmospheric Carbon Dioxide Concentrations**:
   - Format: CSV
   - Source: [IMF Climate Change Data](https://climatedata.imf.org/datasets/9c3764c0efcc4c71934ab3988f219e0e/explore)

3. **Change in Mean Sea Levels**:
   - Format: CSV
   - Source: [IMF Climate Change Data](https://climatedata.imf.org/datasets/b84a7e25159b4c65ba62d3f82c605855/explore)

4. **Climate-related Disasters Frequency**:
   - Format: JSON (Web API)
   - Source: [ArcGIS API](https://services9.arcgis.com/weJ1QsnbMYJlCHdG/arcgis/rest/services/Indicator_11_1_Physical_Risks_Climate_related_disasters_frequency/FeatureServer/0/query?outFields=*&where=1%3D1&f=geojson)

## Data Jargon

- **Baseline Climatology**: A reference period used to calculate anomalies in climate data. For this project, the baseline period is 1951-1980.
- **Satellite Radar Altimeters**: Instruments used in satellites to measure the height of the ocean surface, providing data on sea level changes.

## Exploratory Data Analysis (EDA)

EDA was conducted on the following datasets:

1. **Annual Surface Temperature Change**: Analyzed to understand the global temperature trends.
2. **Atmospheric Carbon Dioxide Concentration**: Studied to observe the trends in CO2 levels.
3. **Mean Sea Level Changes**: Examined to identify the impact of temperature and CO2 levels on sea levels.
4. **Climate-related Disasters Frequency**: Investigated to correlate disaster frequency with environmental changes.

## Data Preparation and Feature Engineering

Data from the various sources were cleaned and processed. Key features were engineered to facilitate the analysis, including:

- Temperature anomalies
- CO2 concentration changes
- Sea level rise rates
- Frequency of natural disasters

## Research Analysis

The analysis revealed significant correlations between:

- CO2 concentration and surface temperature rise
- Surface temperature rise and sea level changes
- Sea level changes and the frequency of natural disasters

A detailed trend analysis showed that CO2 levels have been rising at an increasing rate, which correlates with the observed environmental changes.

## Conclusion

The study concludes that the rise in CO2 levels has a direct impact on global temperatures, sea levels, and the frequency of natural disasters. This highlights the urgent need for measures to control CO2 emissions to mitigate these effects.

## Project Structure

```
├── data
│   ├── CO2_Concentration.csv
│   ├── Surface_Temperature_Change.csv
│   ├── Sea_Level_Changes.csv
│   └── Disaster_Frequency.json
├── notebooks
│   ├── EDA.ipynb
│   ├── Data_Preparation.ipynb
│   └── Research_Analysis.ipynb
├── README.md
└── presentation
    ├── FinalPresentation.pptx
```

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/environmental-impact-analysis.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd environmental-impact-analysis
   ```
3. **Run the Jupyter notebooks** to explore the data and analysis.

## Acknowledgements

We acknowledge the IMF Climate Change Data site and the ArcGIS API for providing the datasets used in this project.

---

Feel free to explore the data and analysis. Contributions and suggestions are welcome!

---

This README provides an overview of the project, including the motivation, data sources, analysis, and findings. For detailed code and analysis, please refer to the individual Jupyter notebooks.
