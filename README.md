# India Air Quality Analysis: AQI Trends, City Intelligence & Pollutant Drivers

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)

## Project Overview

Air pollution is one of India's most critical environmental and public health challenges. This project analyzes Air Quality Index (AQI) data collected across Indian cities to identify pollution trends, seasonal variations, regional differences, and key pollutant drivers affecting air quality.

The project follows a structured end-to-end analytics workflow beginning with raw CPCB data and progressing through preprocessing, exploratory analysis, SQL analytics, and interactive dashboard development.

### Project Objectives

* Analyze AQI trends across Indian cities.
* Identify the most and least polluted cities.
* Understand seasonal pollution patterns.
* Measure the impact of COVID-19 restrictions on AQI.
* Determine key pollutants driving air quality deterioration.
* Build an end-to-end analytics solution using Python, SQL, and Power BI.

---

## Analysis Highlights

### AQI Distribution Analysis

Understanding the overall distribution of AQI values across Indian cities.

![AQI Distribution](images/aqi_distribution.png)

---

### Seasonal AQI Heatmap

Visualizing seasonal and annual pollution patterns.

![AQI Heatmap](images/month_year_heatmap.png)

---

### Most Polluted Cities

Ranking Indian cities based on average AQI.

![Top Polluted Cities](images/top_polluted_cities.png)

---

### AQI vs PM2.5 Relationship

Analyzing the relationship between particulate matter concentration and AQI.

![AQI vs PM2.5](images/aqi_pm25_scatter.png)

---

## Data Pipeline

```text
Raw CPCB Dataset (city_day.csv)
        │
        ▼
Data Preprocessing
        │
        ▼
cleaned_aqi.csv
        │
 ┌──────┼──────────┐
 ▼      ▼          ▼
EDA    SQL      Power BI
```

---

## Repository Structure

```text
.
├── images
│   ├── aqi_distribution.png
│   ├── month_year_heatmap.png
│   ├── top_polluted_cities.png
│   └── aqi_pm25_scatter.png
│
├── notebooks
│   ├── 00_Data_Preprocessing.ipynb
│   ├── 01_Data_Quality_and_Understanding.ipynb
│   ├── 02_Temporal_and_Seasonal_Analysis.ipynb
│   ├── 03_City_Intelligence.ipynb
│   └── 04_Pollutant_Driver_Analysis.ipynb
│
└── README.md
```

---

## Analysis Notebooks

### Data Preprocessing

Purpose:

* AQI validation
* Missing value treatment
* Feature engineering
* Dataset preparation

Notebook:
[00_Data_Preprocessing.ipynb](./notebooks/00_Data_Preprocessing.ipynb)

---

### Data Quality & Understanding

Purpose:

* Dataset exploration
* Data quality assessment
* AQI distribution analysis
* Feature understanding

Notebook:
[01_Data_Quality_and_Understanding.ipynb](./notebooks/01_Data_Quality_and_Understanding.ipynb)

---

### Temporal & Seasonal Analysis

Purpose:

* Annual AQI trends
* Monthly AQI patterns
* Seasonal pollution analysis
* COVID-19 impact assessment

Notebook:
[02_Temporal_and_Seasonal_Analysis.ipynb](./notebooks/02_Temporal_and_Seasonal_Analysis.ipynb)

---

### City Intelligence Analysis

Purpose:

* Most polluted cities
* Cleanest cities
* AQI category distribution
* City-level performance comparison

Notebook:
[03_City_Intelligence.ipynb](./notebooks/03_City_Intelligence.ipynb)

---

### Pollutant Driver Analysis

Purpose:

* Correlation analysis
* AQI vs PM2.5
* AQI vs PM10
* Pollutant importance ranking

Notebook:
[04_Pollutant_Driver_Analysis.ipynb](./notebooks/04_Pollutant_Driver_Analysis.ipynb)

---

## Key Insights

* Average AQI decreased by approximately 44% between 2015 and 2020.
* Winter emerged as the most polluted season across Indian cities.
* July recorded the lowest average AQI levels.
* AQI during the COVID-19 period was significantly lower than the pre-COVID average.
* Ahmedabad ranked among the most polluted cities.
* Aizawl consistently recorded some of the lowest AQI levels.
* PM2.5 demonstrated the strongest relationship with AQI.
* Strong seasonal patterns indicate recurring winter pollution spikes.

---

## Current Status

### Completed

* Data preprocessing
* Data quality assessment
* Exploratory data analysis
* Temporal analysis
* City intelligence analysis
* Pollutant driver analysis

### In Progress

* SQL analytics
* Power BI dashboard development

### Planned

* Interactive dashboard publishing
* Advanced analytics
* AQI forecasting models

---

## Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Statistical Analysis
* Correlation Analysis
* Feature Engineering

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Business Intelligence

* KPI Development
* Trend Analysis
* City-Level Intelligence
* Environmental Analytics

---

## Future Enhancements

* SQL-based analytical reporting
* Interactive Power BI dashboards
* Predictive AQI forecasting
* Real-time AQI monitoring integration
* Automated reporting workflows

---

## Author

**Abhishek Sharma**

Production & Industrial Engineering
Delhi Technological University (DTU)

If you found this project interesting, feel free to explore the notebooks and follow the complete analysis workflow from raw data to actionable insights.
