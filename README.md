# Analyzing Boston Weather Data from 2013 and 2022 through Python Functions
By Emma Bowen

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source and Information](#data-source-and-information)
- [Project Files](#project-files)

## Project Overview
This Python project addresses how average temperature and precipitation varies in Boston in March 2013 and March 2022 through the analysis of the *Boston Weather 2013-2023* dataset (Meher, 2023). This project includes the final jupyter notebook and corresponding plots derived from this research, which utilize the Python packages `pandas`, `seaborn`, and `matplotlib`. This Python project showcases my ability to pipeline functions, clean/filter data, and create effective visualizations.

## Data Source and Information
- **Title**: *Boston Weather 2013-2023*
- **Creator**: Swaroop Meher (2023)
- **License**: CC0: Public Domain
- **Full Citation**: Meher, S. (2023). *Boston Weather 2013-2023*. Kaggle. https://www.kaggle.com/datasets/swaroopmeher/boston-weather-2013-2023

## Project Files
- [boston-weather-analysis.ipynb](#boston-weather-analysis.ipynb)   
boston-weather-analysis/precipitation_march.png   
boston-weather-analysis/temperature_march.png

## Python Packages
- `pandas`
- `seaborn`
- `matplotlib`

## Pipeline Overview
  1. Import the CSV file
  2. Clean the data to remove NA and duplicate values
  3. Print summary statistics
  4. Convert the time column and extract years, months, and days
  5. Filter and save only March weather in 2013 as a new variable
  6. Filter and save only March weather in 2022 as a new variable
  7. Calculate average temperature and precipitation for filtered data variables
  8. Compare the averages from 2013 and 2022 by plotting the results

## Summary
In March 2013, Boston averaged a lower maximum air temperature (6.18°C) and greater precipitation (4.37 mm) than in March 2022, which had both a warmer average maximum air temperature (10.1°C) and lower precipitation (2.49 mm).
While more research would be needed to study weather patterns within this region, these results raise the question of how climate change has affected areas that historically received more rain and colder weather, as the almost 10-year difference reflects significant changes, including increased average maximum temperatures and decreased average precipitation.

## References
*Boston (MA) Monthly Rainfall & Precipitation*. (2026). Weather and Climate. https://weather-and-climate.com/average-monthly-precipitation-Rainfall,Boston,United-States-of-America
Meher, S. (2023). *Boston Weather 2013-2023*. Kaggle. https://www.kaggle.com/datasets/swaroopmeher/boston-weather-2013-2023
