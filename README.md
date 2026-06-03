# European Airport Traffic Study & Analysis (2020–2025)

## Overview

This project explores European airport passenger traffic trends between 2020 and 2025, focusing on the impact of COVID-19, post-pandemic recovery patterns, regional differences, and structural variations in air travel demand.

Using Eurostat aviation data, the analysis combines data cleaning, exploratory data analysis (EDA), statistical analysis, and data storytelling techniques to uncover how passenger traffic evolved across European countries during one of the most disruptive periods in aviation history.

---

## Project Objectives

The study aims to:

* Analyse the impact of COVID-19 on European airport traffic.
* Identify recovery trends across European countries.
* Examine seasonal passenger traffic patterns.
* Compare national and international travel dependence.
* Evaluate regional differences in recovery speed and stability.
* Develop visual narratives using data storytelling principles.

---

## Dataset

**Source:** Eurostat Air Transport Statistics

### Coverage

* Time Period: January 2020 – July 2025
* 40,000+ observations
* 36 European countries and regions
* Monthly passenger traffic records

### Key Variable

* Passengers Carried (PAS_CRD)

---

## Data Preparation

The following preprocessing steps were applied:

* Column standardisation
* Datetime conversion
* Missing value analysis
* Outlier detection and treatment
* Country name correction
* Removal of EU aggregate records
* Elimination of duplicate transport categories

### Outlier Treatment

Instead of removing extreme values, an IQR-based capping strategy was applied to preserve genuine peak traffic observations while reducing distortion.

---

## Exploratory Data Analysis (EDA)

### Distribution Analysis

* Passenger volume distributions
* Histogram and density analysis
* Skewness assessment

### Seasonal Analysis

* Monthly traffic patterns
* COVID vs Post-COVID comparison
* Seasonal demand recovery

### Statistical Diagnostics

* Missing value mechanisms
* Data integrity checks
* Outlier diagnostics

---

## Research Questions

### 1. Traffic Recovery Analysis

How did airport traffic change before, during, and after COVID-19?

### 2. Regional Recovery Patterns

Which European countries recovered fastest and contributed most to traffic growth?

### 3. Travel Structure Analysis

How do national and international passenger traffic shares differ across countries?

---

## Key Findings

### COVID Impact

* Passenger traffic collapsed sharply during early 2020.
* Recovery began gradually in 2021 and accelerated during 2022–2024.
* Seasonal travel patterns re-emerged after restrictions were lifted.

### Regional Differences

High-growth recovery countries included:

* Cyprus
* Croatia
* Slovenia

Countries with slower recovery included:

* Greece
* Portugal
* Norway

### Structural Travel Dependence

* Smaller countries relied heavily on international travel.
* Larger countries maintained stronger domestic aviation networks.
* Tourism-focused economies were more sensitive to border restrictions.

---

## Visualisations Included

* Airport Traffic Recovery Trends
* Outlier Analysis Dashboard
* Passenger Volume Distribution
* COVID vs Post-COVID Violin Plots
* Regional Recovery Comparison
* National vs International Traffic Analysis
* Recovery Speed vs Stability Analysis

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Data Storytelling Techniques
* Statistical Analysis
* Exploratory Data Analysis (EDA)

---

## Repository Structure

```text
airporttraffic_data_visualization_storytelling/
│
├── data/
│   └── README.md
│
├── src/
│   └── European_Airport_Traffic_Analysis.ipynb
│
├── outputs/
│   ├── traffic_recovery_trends.png
│   ├── outlier_analysis.png
│   ├── passenger_distribution.png
│   ├── covid_postcovid_violin.png
│   ├── regional_recovery.png
│   ├── national_vs_international.png
│   └── recovery_stability.png
│
└── README.md
```

---

## Business Value

This analysis can support:

* Aviation Policy Planning
* Airport Capacity Forecasting
* Tourism Recovery Assessment
* Transport Infrastructure Planning
* Post-Crisis Resilience Analysis

---

## Future Enhancements

* Airport-level analysis
* Forecasting future passenger demand
* Integration of economic indicators
* Machine learning-based traffic prediction
* Interactive dashboard development

---

## Author

**Veera Suresh Akuthota**
MSc Data Science
University of Roehampton, London

---

## Disclaimer

This project was completed for academic purposes using publicly available Eurostat aviation data.
