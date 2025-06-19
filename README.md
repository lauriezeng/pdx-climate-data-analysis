# Climate Data Analysis for Portland, OR

## Project Overview

This project provides a comprehensive analysis of historical climate data from Portland International Airport (OR) for the period 2004–2024. The analysis covers key weather parameters such as air temperature, precipitation, and groundwater levels (GWL). Using data sourced from NOAA and USGS, the project aims to identify climate patterns, trends, and extreme weather events that have occurred over the last two decades, with a focus on understanding the effects of climate change.

## Project Setup

### Dependencies:
- Python 3

### Required libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `dataretrieval`

### Installation:
To install the required libraries, run the following commands:

```bash
pip install numpy==1.23.4
pip install pandoc
pip install pandas
pip install matplotlib
pip install seaborn
pip install scipy
pip install dataretrieval
```

### Data Sources:
- **NOAA**: Provides air temperature and precipitation data.
- **USGS**: Provides groundwater level data.

## Analysis Summary

### 1. Air Temperature Analysis:
- **Data Preparation**: Cleaned and filtered air temperature data (TMAX and TMIN) from Portland Airport.
- **Findings**:
  - Identified seasonal temperature patterns, with consistent temperature lows in winter and highs in summer.
  - The hottest day in the last two decades was June 28, 2021, and the coldest day was January 13, 2017.
  - A distribution analysis showed temperature extremes were rare but more frequent in summer.

### 2. Precipitation Analysis:
- **Data Preparation**: Extracted precipitation data from the NOAA database.
- **Findings**:
  - Portland experiences distinct wet seasons, particularly during winter and early spring.
  - Most days (57.5%) were dry, but significant rainfall events occurred regularly, representing Portland's reputation for frequent rain.

### 3. Groundwater Level (GWL) Analysis:
- **Data Preparation**: Groundwater level data was retrieved via the USGS NWIS API.
- **Findings**:
  - Seasonal fluctuations in GWL were observed, corresponding to precipitation patterns.
  - The most common groundwater levels were between 42 to 44 feet, with extremes being less frequent.

## Key Visualizations:
- Time series plots of air temperatures, precipitation, and groundwater levels.
- Histograms of temperature distributions and GWL distribution with a smooth Kernel Density Estimation (KDE) line.
- Bar and pie charts to show the proportion of hot and cold days over the years.

## Conclusion

This analysis highlights key climate trends in Portland, including a rise in hot days over the last two decades, stable groundwater levels, and the city's characteristic wet weather. These findings contribute to understanding the impact of climate change on Portland's weather patterns and can support future planning for environmental and climate-related challenges.
