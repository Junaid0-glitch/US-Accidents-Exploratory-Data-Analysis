# US Accidents Exploratory Data Analysis

## Overview

The **US Accidents** dataset, sourced from [Kaggle](https://www.kaggle.com), provides detailed information about traffic accidents in the United States. This dataset contains over 7 million records and includes features such as location, time, weather conditions, and more. While it does not include data for New York, it remains a valuable resource for understanding accident patterns and identifying potential strategies to improve road safety and prevent accidents.

## Data Preparation and Cleaning

1. **Loading the Dataset**: The dataset was loaded into a Pandas DataFrame for processing.
2. **Initial Exploration**: General information about the dataset and its columns was examined to understand the data structure.
3. **Handling Missing Values**: Missing or incorrect values were identified and addressed to ensure data quality.
4. **Libraries Used**: Key libraries included:
   - `pandas` for data manipulation
   - `seaborn` and `matplotlib` for visualizations
   - `folium` for interactive maps
   - `scipy.stats` for statistical analysis

## Exploratory Analysis and Visualization

### Key Columns Analyzed:

1. **City**: Examined the distribution of accidents across cities.
2. **Start Time**: Analyzed accident trends based on time of day and day of the week.
3. **Start Latitude and Longitude**: Visualized accident locations using maps.
4. **Temperature**: Investigated how temperature variations correlate with accidents.
5. **Weather Conditions**: Explored the impact of different weather conditions on accident frequency.

### Insights:

- **City-Level Analysis**:
  - The number of accidents per city decreases exponentially.
  - Less than 8% of cities report more than 1,000 accidents per year.
  - Over 1,023 cities have reported just one accident.
  - Miami, Houston, and Los Angeles are the top three cities with the most accidents.

- **Time-Based Analysis**:
  - Most accidents occur between **7 AM - 8 AM** and **4 PM - 6 PM**, likely due to commuting patterns.
  - Fewer accidents happen on weekends compared to weekdays.

- **Seasonal Trends**:
  - The majority of accidents (2.66 million) occur during the **Fall** season, followed by **Winter**.
  - **Summer** and **Spring** have significantly fewer accidents, indicating a potential link to weather or travel behavior.

- **Weather and Environmental Factors**:
  - Weather conditions such as rain, fog, or snow correlate with higher accident frequencies.

## Statistical Analysis

- **T-Tests and Chi-Square Tests**:
  - Conducted hypothesis testing to evaluate significant differences in accident patterns based on time, location, and weather.
- **Spearman Correlation**:
  - Assessed relationships between numerical variables like temperature and accident counts.

## Tools Used

- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Folium
- **Statistical Methods**: T-tests, Chi-square tests, Correlation Analysis
- **Visualization Tools**: Folium for mapping accident hotspots

## Summary and Conclusion

- **General Trends**:
  - Accidents are concentrated in a small percentage of cities, with urban areas like Miami, Houston, and Los Angeles being most affected.
  - Commuting hours during weekdays see the highest number of accidents.

- **Seasonal and Weather Impacts**:
  - Fall and Winter seasons are associated with higher accident rates.
  - Weather conditions play a significant role in accident frequency, highlighting the need for tailored safety measures during adverse conditions.

This analysis demonstrates the potential of the US Accidents dataset to uncover actionable insights, aiding policymakers and researchers in designing effective accident prevention strategies.

