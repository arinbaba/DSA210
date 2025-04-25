# DSA210

# Magnesium Intake and Sleep Duration Analysis

## Introduction
Understanding the factors that influence sleep quality is essential for both personal health and broader clinical research. Magnesium, an essential mineral, has been associated with numerous physiological processes including nerve transmission, muscle function, and circadian rhythm regulation. However, its direct impact on different aspects of sleep remains an area of growing interest. This project investigates whether daily magnesium intake correlates with total sleep duration, sleep quality scores, and the distribution across various sleep stages (REM, Deep, and Light Sleep). Using a synthetically generated dataset inspired by real-world wearable technology data, we aim to uncover potential patterns and relationships through exploratory data analysis, statistical testing, and visualization techniques.

## Project Overview
This project explores the potential relationship between daily magnesium intake and various sleep-related metrics, including total sleep duration, sleep quality, and different sleep stages (REM, Deep, and Light Sleep). Magnesium plays a crucial role in numerous biological processes, including nerve function and sleep regulation. This study aims to determine whether fluctuations in magnesium intake correlate with measurable changes in sleep patterns, using synthetically generated data that mimics 50 days of tracking via wearable devices such as an Apple Watch.

The primary objective of the analysis is to understand if magnesium consumption impacts overall sleep quality, and if so, to which sleep parameters it is most strongly linked.

## Dataset Description
The dataset consists of the following variables collected over 50 days:
- **Magnesium_mg**: Daily magnesium intake in milligrams.
- **Sleep_Hours**: Total sleep duration in hours.
- **Sleep_Score**: An aggregate sleep quality score (0-100 scale) inspired by wearable devices.
- **REM_Sleep_Hours**: Duration of REM (Rapid Eye Movement) sleep in hours.
- **Deep_Sleep_Hours**: Duration of deep sleep in hours.
- **Light_Sleep_Hours**: Duration of light sleep in hours.

The data includes mild randomness and noise to reflect realistic variability.

## Methods
- **Exploratory Data Analysis (EDA)**: Conducted to understand the basic distribution and relationships within the dataset using descriptive statistics, correlation matrices, histograms, boxplots, heatmaps, and pairplots.
- **Correlation Analysis**: Pearson correlation coefficients were calculated to quantify the strength and direction of linear relationships between magnesium intake and each sleep parameter.
- **Hypothesis Testing**: Statistical tests were performed for each pair to formally assess the significance of observed correlations. A 5% significance level (α = 0.05) was used to determine if relationships were statistically meaningful.

## Hypotheses
For each sleep metric analyzed, the following hypotheses were tested:
- **Null Hypothesis (H₀)**: There is no significant correlation between magnesium intake and the sleep metric.
- **Alternative Hypothesis (H₁)**: There is a significant correlation between magnesium intake and the sleep metric.

Hypothesis testing results guided the interpretation of whether magnesium intake meaningfully influences various sleep dimensions.

## Results Summary
- **Sleep Hours**: Displayed a mild positive correlation with magnesium intake; results were borderline significant.
- **Sleep Score**: A slightly stronger positive correlation observed, suggesting magnesium may have a minor influence on perceived sleep quality.
- **REM Sleep Hours**: Moderate positive correlation, supporting prior research suggesting magnesium could promote REM sleep.
- **Deep Sleep Hours**: Very weak or no correlation detected.
- **Light Sleep Hours**: Weak positive correlation, not statistically significant.

Overall, magnesium showed varying degrees of association with sleep, being more connected to REM sleep and sleep score rather than total sleep hours or deep/light sleep.

## Visualizations Included
- **Summary Statistics**: Overview of the mean, median, standard deviation, etc.
- **Correlation Heatmap**: Visual map of inter-variable relationships.
- **Histograms**: Distribution plots for each feature.
- **Boxplots**: Outlier detection and spread visualization for each feature.
- **Pairplots**: Multivariate relationships across all pairs of features.
- **Scatterplots**: Detailed plots between magnesium intake and each sleep variable.

No external data downloads are needed.

## Limitations and Future Work
- The dataset is synthetic and may not perfectly represent real-world variability.
- Other confounding factors (diet, stress, exercise) affecting sleep were not modeled.
- Future studies could incorporate larger datasets and apply multivariate regression or machine learning models to explore more complex relationships.

---

