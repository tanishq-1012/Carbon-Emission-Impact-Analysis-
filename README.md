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

### 3. Correlation Analysis

* Pearson Correlation Coefficient: ~0.96

* A strong linear correlation exists between rising CO₂ and global warming.

### 4. Linear Regression

* Linear trend lines applied to both datasets.

* Regression results show that both variables have statistically significant upward trends over time.

### 5. Seasonal Variation

Average CO₂ concentration per calendar month across years.

Highest levels around April–May; lowest around September–October, suggesting seasonal biosphere absorption.

## 📌 Visualizations

- **Time-Series Line Charts** (Plotly)
- **Correlation Heatmap** (Seaborn)
- **CO₂ vs. Temperature Scatter Plot**
- **Regression Line Fitting**
- **Seasonal Line Graph (Monthly CO₂ Averages)**

## Time-Series Analysis

Next, we’ll examine how temperature changes and CO₂ concentrations have evolved overtime and the relationships between them:

<img width="1149" alt="Screenshot 2025-05-16 at 5 44 25 PM" src="https://github.com/user-attachments/assets/af90bdf0-61e5-442b-a473-114734570920" />

The time-series graph shows a consistent increase in CO₂ concentrations (measured in ppm) over the years, which indicates the accumulation of greenhouse gases in the atmosphere. Simultaneously, a slight upward trend in global temperature change suggests that rising CO₂ levels are associated with global warming. The temporal alignment supports the hypothesis of CO₂’s significant contribution to temperature increase.

<img width="1149" alt="Screenshot 2025-05-16 at 5 44 39 PM" src="https://github.com/user-attachments/assets/a9d00495-e6dd-4e19-b800-340362304da9" />

The heatmap reveals a strong positive correlation (0.96) between CO₂ concentrations and temperature changes. This statistical relationship reinforces the observation that higher CO₂ levels are closely linked with increasing global temperatures, which highlights the importance of addressing carbon emissions to mitigate climate change.

<img width="1149" alt="Screenshot 2025-05-16 at 5 44 52 PM" src="https://github.com/user-attachments/assets/93d47cca-4d89-4170-b96e-ff8b55339dbb" />

The scatter plot shows a clear linear trend, where higher CO₂ concentrations correspond to greater temperature changes. This visual evidence underscores the direct relationship between CO₂ emissions and global warming, which provides further support for policies targeting reductions in carbon emissions to combat climate impacts.

## Trends and Seasonal Variations Analysis

Now, let’s identify long-term trends and seasonal variations in the data using linear regression:

<img width="1149" alt="Screenshot 2025-05-16 at 5 45 06 PM" src="https://github.com/user-attachments/assets/9cdf66b6-da41-4d73-8fe0-b92b94e9bd16" />

The graph shows the linear trends in both temperature change and CO₂ concentrations over time, represented by their respective slopes. The CO₂ trend has a much steeper slope (0.32) compared to temperature (0.03), which indicates a faster rate of increase in CO₂ emissions relative to temperature change. This suggests that while CO₂ levels are rising rapidly, the temperature impact, though slower, is accumulating steadily and may have long-term consequences.

<img width="1149" alt="Screenshot 2025-05-16 at 5 45 18 PM" src="https://github.com/user-attachments/assets/76c9db14-5a02-4496-b1bc-8275aca1bdd8" />

The above graph highlights the seasonal fluctuations in CO₂ concentrations, which peak during late spring and early summer (around May) and reach the lowest levels in fall (around September). These variations are likely due to natural processes such as plant photosynthesis, which absorbs CO₂ during the growing season, and respiration, which releases CO₂ in the off-season. This seasonal cycle underscores the role of natural carbon sinks in moderating atmospheric CO₂ levels.

## Correlation and Causality Analysis

To quantify the relationship between CO₂ and temperature anomalies, we will now compute Pearson and Spearman correlation coefficients. And to investigate whether changes in CO₂ cause temperature anomalies, we will perform Granger Causality tests:

<img width="446" alt="Screenshot 2025-05-16 at 5 45 46 PM" src="https://github.com/user-attachments/assets/bd431149-ff5a-4bba-8d27-170186b8d70f" />

Pearson Correlation (0.9554) indicates a very strong linear relationship between CO₂ concentrations and temperature changes. Spearman Correlation (0.9379) indicates a very strong monotonic relationship between CO₂ concentrations and temperature changes.

Granger Causality Test: The p-values for lags 1, 2, and 3 are as follows:

Lag 1: 0.0617 (slightly above the common significance threshold of 0.05, suggesting weak evidence for causality).

Lag 2: 0.6754 (not significant, no evidence of causality).

Lag 3: 0.2994 (not significant, no evidence of causality).
There is a very strong correlation between CO₂ concentrations and temperature changes. 

However, Granger Causality tests do not provide strong evidence that changes in CO₂ concentrations directly cause changes in temperature within the lags tested.

## Lagged Effects Analysis

Now, we will analyze whether CO₂ concentrations from previous years (lagged values) influence current temperature anomalies. To do this, we will create lagged variables for CO₂ concentrations, specifically shifting the data by 1, 2, and 3 years. These lagged values will allow us to test if historical CO₂ levels have a delayed impact on temperature changes.

After creating these lagged variables, we will fit an Ordinary Least Squares (OLS) regression model. This model will use current and lagged CO₂ levels as predictors to estimate their contribution to current temperature anomalies. By examining the regression results, we will determine:

1. How strongly current CO₂ levels affect temperature changes.
2. Whether CO₂ levels from previous years have a significant impact

<img width="575" alt="Screenshot 2025-05-16 at 5 46 03 PM" src="https://github.com/user-attachments/assets/5a6e5af7-dcf3-43c6-9623-017e1409a391" />

<img width="660" alt="Screenshot 2025-05-16 at 5 46 28 PM" src="https://github.com/user-attachments/assets/0c65236b-222d-47d7-8b67-7e5f8830b4e8" />

The OLS regression results indicate a strong relationship between CO₂ concentration and temperature change, with an R-squared value of 0.949, meaning 94.9% of the variance in temperature change is explained by the model. The coefficient for CO₂ concentration (0.3245) is statistically significant (p < 0.05), which suggests a positive association between CO₂ levels and temperature change.

## Clustering Climate Patterns

Next, we group years based on similarities in temperature anomalies and CO₂ concentrations using K-Means clustering:

<img width="1162" alt="Screenshot 2025-05-16 at 5 47 03 PM" src="https://github.com/user-attachments/assets/69b5e798-6775-4e1e-b028-7912656f7637" />

The clustering graph segments years into three distinct climate patterns based on CO₂ concentration and temperature change: low CO₂ and temperature (green), moderate CO₂ and temperature (orange), and high CO₂ and temperature (blue). The progression from green to orange and then to blue clusters reflects a clear trend of increasing temperature change corresponding to rising CO₂ levels, effectively illustrating the correlation between greenhouse gas concentrations and global temperature variations.

This clustering emphasizes the cumulative and escalating impact of carbon emissions on global temperature patterns, which illustrates the need for targeted interventions to mitigate future increases.

## Predicting Temperature Changes Under What If Analysis

Now, we will use a simple linear regression model to simulate how changes in CO₂ concentrations might influence global temperatures. By leveraging the historical relationship between CO₂ concentrations and temperature anomalies, this model allows us to predict the potential impact of different emission scenarios.

First, we will train a linear regression model with CO₂ concentrations as the input and temperature anomalies as the output. Once the model is trained, we can simulate hypothetical scenarios where CO₂ concentrations increase or decrease by a specific percentage.

For each scenario, we will adjust the current average CO₂ concentration by the specified percentage, feed it into the model, and predict the corresponding temperature anomaly. The scenarios we simulate include:

**Increase CO₂ by 10%**: Predict the rise in temperature anomalies.
**Decrease CO₂ by 10%**: Estimate the cooling effect.
**Increase CO₂ by 20%**: Analyze the impact of more aggressive emissions growth.
**Decrease CO₂ by 20%**: Evaluate the benefit of significant emission reductions.

<img width="549" alt="Screenshot 2025-05-16 at 5 47 27 PM" src="https://github.com/user-attachments/assets/330a731b-a819-43db-abc4-f252859a9083" />

A 10% increase in CO₂ results in a notable rise in temperature anomalies, which demonstrates the sensitivity of global temperatures to CO₂ levels. Conversely, a 10-20% reduction in CO₂ could lead to significant cooling effects, which will potentially reverse some warming trends.

## 📌 Visualizations

- **Time-Series Line Charts** (Plotly)
- **Correlation Heatmap** (Seaborn)
- **CO₂ vs. Temperature Scatter Plot**
- **Regression Line Fitting**
- **Seasonal Line Graph (Monthly CO₂ Averages)**

## 🧠 Key Takeaways

- There is a clear **causal relationship** between increasing CO₂ levels and global temperature anomalies.
- Seasonal patterns in CO₂ suggest natural absorption cycles (e.g., vegetation photosynthesis).
- Quantitative evidence supports urgent climate policy decisions focused on reducing emissions.

