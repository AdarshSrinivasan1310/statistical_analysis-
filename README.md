# statistical_analysis-
# README: Statistical Analysis in R

## Overview
This R script performs statistical analysis on climbing success rates in relation to various weather parameters. It integrates data from two datasets, processes them, conducts exploratory data analysis, hypothesis testing, and builds a predictive model.

## Requirements
Ensure the following R packages are installed before running the script:
```r
install.packages(c("ggplot2", "corrplot", "dplyr", "car", "broom"))
```

## Data Sources
- `climbing_statistics.csv`: Contains data on climbing success rates.
- `Rainier_Weather.csv`: Contains weather statistics.

## Key Steps in the Script
1. **Load Libraries & Data**
   - Reads CSV files into data frames.
   - Converts date columns to Date format.
   - Merges the two datasets based on the `Date` column.

2. **Exploratory Data Analysis (EDA)**
   - Calculates correlation matrix.
   - Generates visualizations (scatter plots, histograms, and boxplots) for weather variables and success percentage.

3. **Central Tendencies Calculation**
   - Computes mean and median for key variables.

4. **Normality Check**
   - Uses QQ plots to assess normality of key variables.

5. **Hypothesis Testing**
   - Performs a Z-test to determine if there's a significant difference in climbing success rates between high and low success levels.

6. **Linear Regression Model**
   - Builds a regression model to predict success percentage based on weather conditions.
   - Conducts ANOVA analysis.
   - Makes predictions using sample weather values.

## Output & Interpretation
- **Plots:** Various visualizations to analyze relationships between weather conditions and climbing success.
- **Statistical Metrics:** Mean, median, and correlation coefficients.
- **Model Summary:** Regression analysis and ANOVA results.
- **Predictions:** Success rate estimates for new weather data.

## How to Run the Script
1. Ensure all dependencies are installed.
2. Place the CSV files in the working directory.
3. Run the script in an R environment (e.g., RStudio).

## Notes
- Ensure that the dataset paths are correctly specified before execution.
- Modify parameters if needed to analyze different relationships.

## Author
[Your Name]

