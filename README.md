
# Exploratory Data Analysis (EDA) on Sales Data

## Overview
This project involves a comprehensive Exploratory Data Analysis (EDA) on a dataset containing sales data from multiple stores. The primary goal is to uncover valuable insights about the relationship between weekly sales and various factors, including store-specific attributes, economic indicators, and external influences such as holidays.

## Key EDA Steps

### 1. Data Cleaning and Preprocessing
- Checked for and handled missing data.
- Converted date-related columns into separate year and month columns for better trend analysis.
- Ensured all data types were appropriately formatted for analysis.

### 2. Univariate Analysis
- **Box Plots:** Used to visualize the distribution and identify outliers for Weekly Sales, and to compare sales between holiday and non-holiday weeks.
- **Histograms:** Provided a deeper understanding of the distribution of Weekly Sales, Fuel Price, CPI, and Unemployment variables.
- **Summary Statistics:** Computed for each variable to understand their central tendency and spread.

### 3. Bivariate Analysis
- **Scatter Plots:** Examined the relationships between Weekly Sales and other key variables such as Fuel Price, CPI, and Unemployment, helping to identify any linear or non-linear relationships.
- **Correlation Heatmap:** Showed the strength of relationships between numerical variables, revealing moderate correlations between Weekly Sales and variables like Fuel Price and CPI.

### 4. Trend Analysis
- **Line Plots:** Demonstrated the trend of weekly sales over time, highlighting how sales fluctuated across different months and years.
- **Pivot Table:** Created to show the trend of monthly sales across multiple years, providing insights into how different years performed.

### 5. Comparative Analysis
- **Bar Plots:** Compared the average weekly sales across different stores, revealing performance variance between stores.
- **Box Plots:** Compared holiday and non-holiday weeks to provide insights into the impact of holidays on sales.

### 6. Seasonality and Insights
- Analyzed weekly sales patterns over time, identified potential seasonal trends, and assessed outliers that may warrant further investigation.
- Gleaned insights about the performance of stores based on average sales and outlier detection.

## Key Findings
- **Holiday Impact:** Holiday weeks tended to have similar median sales to non-holiday weeks, but with more consistent values.
- **Store Performance:** Noticeable variation in sales across stores, with some outperforming others significantly.
- **Economic Indicators:** Fuel Price and CPI did not show a strong linear relationship with weekly sales, suggesting other external factors might be influencing sales trends.
- **Trends Over Time:** Sales showed significant fluctuations across the years, indicating potential seasonality, promotions, or other business-related factors.

## Limitations
- **Limited Data:** The analysis was based on data spanning a limited number of years, which may not provide a full picture of long-term trends.
- **External Factors:** Variables such as marketing efforts, store location, and competition were not included in the dataset, limiting the scope of the analysis.

## Conclusion
This EDA provided valuable insights into the sales data, highlighting key patterns, trends, and areas for further investigation. The next steps could involve feature engineering, building predictive models, or optimizing business strategies based on the identified insights.

---
