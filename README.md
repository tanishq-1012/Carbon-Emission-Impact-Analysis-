# 🌍 Carbon-Emission-Impact-Analysis

This project investigates the relationship between global atmospheric CO₂ concentrations and temperature anomalies over time. Using Python and publicly available datasets, it explores statistical patterns, trends, correlations, and seasonal variations to better understand the impact of carbon emissions on global warming.
Climate change is one of the most critical challenges of our time, with rising carbon emissions playing a pivotal role in driving global temperature anomalies. Analyzing the relationship between CO₂ concentrations and temperature changes provides valuable insights into the underlying patterns and trends that shape our planet’s climate.

## 📊 Project Objective

To analyze how rising CO₂ levels correlate with global temperature anomalies and identify seasonal patterns that contribute to the broader climate change narrative.

## 📁 Datasets Used

we aim to explore the impact of carbon emissions on global temperatures. The focus will be on identifying historical trends, detecting anomalies, and simulating potential future scenarios to understand how changes in CO₂ concentrations influence temperature anomalies.

For this, we will work with two primary datasets:

1. One containing annual temperature changes across multiple countries and decades,

2. Another featuring monthly CO₂ concentrations measured globally.

By combining these datasets, we will investigate correlations, detect patterns over decades, and use predictive modelling to simulate “what-if” scenarios. This data-driven approach will provide actionable insights into the connection between carbon emissions and climate change, which can offer valuable context for sustainable policy-making.

1. **Global CO₂ Concentrations**
   - Source: [NOAA ESRL Mauna Loa CO₂](https://gml.noaa.gov/ccgg/trends/)
   - Format: Monthly average ppm values.

2. **Global Temperature Anomalies**
   - Source: [NASA GISS Surface Temperature Analysis (GISTEMP)](https://data.giss.nasa.gov/gistemp/)
   - Format: Monthly global land-ocean temperature anomalies in °C.

## 🧰 Technologies & Libraries

- **Python 3.10+**
- `pandas` – Data cleaning and manipulation  
- `numpy` – Statistical operations  
- `matplotlib`, `seaborn`, `plotly` – Data visualization  
- `scikit-learn` – Linear regression modeling  
- `calendar` – Monthly name conversion for seasonal analysis

## Dataset

Now let's get started with the task of Carbon Emissions impact Analysisby importig the necesssary Python libraries and the dataset 

<img width="724" alt="Screenshot 2025-05-16 at 5 43 18 PM" src="https://github.com/user-attachments/assets/28149ca3-2a6d-4801-ac85-850d462b4ec8" />

We are using two datasets:

1. Temperature Data: Annual temperature anomalies measured in degrees Celsius across decades.
2. CO₂ Data: Monthly global atmospheric CO₂ concentrations in parts per million (ppm).

## 🧰 Technologies & Libraries

- **Python 3.10+**
- `pandas` – Data cleaning and manipulation  
- `numpy` – Statistical operations  
- `matplotlib`, `seaborn`, `plotly` – Data visualization  
- `scikit-learn` – Linear regression modeling  
- `calendar` – Monthly name conversion for seasonal analysis

Now, let's calculate key statistics for tempreture changes and CO2 concentrations, such as mean, median, and varience:

<img width="470" alt="Screenshot 2025-05-16 at 5 43 49 PM" src="https://github.com/user-attachments/assets/34b7a4ba-e2cb-405d-8aca-855b70fc7d61" />

The mean temperature change is approximately 0.54°C, with a median of 0.47°C and a variance of 0.43, indicating slight variability in temperature anomalies. For CO₂ concentrations, the mean is 180.72 ppm, the median is significantly higher at 313.84 ppm, and the variance is 32,600, which reflects substantial variability in CO₂ levels over the dataset’s timeframe. This highlights the stronger fluctuation in CO₂ data compared to temperature changes.

## 📈 Key Analyses

### 1. Statistical Summary

* Mean, median, standard deviation, variance, min, and max for both datasets.

* Insight: CO₂ concentrations show a much higher range and variance than temperature anomalies.

### 2. Time-Series Visualization

* Line plots of CO₂ levels and temperature anomalies from 1958 to 2023.

* Both variables show a clear increasing trend.

##E 3. Correlation Analysis

* Pearson Correlation Coefficient: ~0.96

* A strong linear correlation exists between rising CO₂ and global warming.

### 4. Linear Regression

* Linear trend lines applied to both datasets.

* Regression results show that both variables have statistically significant upward trends over time.

### 5. Seasonal Variation

Average CO₂ concentration per calendar month across years.

Highest levels around April–May; lowest around September–October, suggesting seasonal biosphere absorption.
