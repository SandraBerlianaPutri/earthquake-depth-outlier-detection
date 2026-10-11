# Earthquake Depth Outlier Detection Using R

## About
This project applies Exploratory Data Analysis (EDA) and robust statistical methods to Indonesian earthquake data. The analysis examines earthquake depth distributions, tests normality, and identifies potential outliers using conventional and adjusted boxplots.

## Full Analysis
The complete analysis, including the R code and visualizations, is available on RPubs:

[**View the Full Analysis on RPubs**](https://rpubs.com/sandraberlianaputri/earthquake-depth-adjusted-boxplot)

## Data
- **Source:** [Indonesian Agency for Meteorology, Climatology, and Geophysics (BMKG)](https://www.bmkg.go.id/)
- **Collection Date:** February 26, 2024
- **Observation Period:** February 19–26, 2024
- **Geographic Coverage:** Indonesia
- **Sample Size:** 167 earthquake records
- **Variables:** Earthquake time, latitude, longitude, magnitude, depth, and location

## Methods

1. **Data Preparation** — Import earthquake records and select earthquake depth as the primary variable of interest.
2. **Descriptive Statistics** — Calculate summary statistics, including the mean, median, quartiles, standard deviation, range, skewness, and kurtosis.
3. **Distribution Analysis** — Use frequency tables, histograms, and density curves to examine the distribution of earthquake depths.
4. **Conventional Outlier Detection** — Apply the IQR method with standard boxplot fences to identify potential outliers.
5. **Robust Outlier Detection** — Calculate the medcouple statistic and apply adjusted boxplot fences to account for the skewness of the distribution.
6. **Normality Testing** — Perform the Shapiro–Wilk test to assess whether earthquake depth data follow a normal distribution.
7. **Result Interpretation** — Compare the conventional and adjusted boxplot results and examine the implications of the data's skewed distribution for outlier detection.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in statistical modeling and data analysis.
