# Analyzing Boston Weather Data from 2013 and 2022 through Python Functions
By Emma Bowen

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source and Information](#data-source-and-information)
- [Project Files](#project-files)
- [Required Python Packages](#required-python-packages)
- [Pipeline Overview](#pipeline-overview)
- [Results](#results)
- [Summary](#summary)
- [References](#references)
- [About the Author](#about-the-author)

## Project Overview
This Python project addresses how average temperature and precipitation varies in Boston in March 2013 and March 2022 through the analysis of the *Boston Weather 2013-2023* dataset (Meher, 2023). This project includes the final jupyter notebook and corresponding plots derived from this research, which utilize the Python packages `pandas`, `seaborn`, and `matplotlib`. This Python project showcases my ability to pipeline functions, clean/filter data, and create effective visualizations.

## Data Source and Information
- **Title**: *Boston Weather 2013-2023*
- **Creator**: Swaroop Meher (2023)
- **License**: CC0: Public Domain
- **Full Citation**: Meher, S. (2023). *Boston Weather 2013-2023*. Kaggle. https://www.kaggle.com/datasets/swaroopmeher/boston-weather-2013-2023

## Project Files
- [boston-weather-analysis.ipynb](boston-weather-analysis.ipynb)   
- [precipitation_march.png](precipitation_march.png)
- [temperature_march.png](temperature_march.png)

## Required Python Packages
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

## Results
In March 2013, Boston averaged a lower maximum air temperature (6.18°C) and greater precipitation (4.37 mm) than in March 2022, which had both a warmer average maximum air temperature (10.1°C) and lower precipitation (2.49 mm).
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/8346fcc6-f497-427e-8b03-5ef3a3432965" />
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/56f2bacc-828b-4137-81ae-6b9c753c895f" />

## Summary
While more research would be needed to study weather patterns within this region, these results raise the question of how climate change has affected areas that historically received more rain and colder weather, as the almost 10-year difference reflects significant changes, including increased average maximum temperatures and decreased average precipitation.

## References
*Boston (MA) Monthly Rainfall & Precipitation*. (2026). Weather and Climate. https://weather-and-climate.com/average-monthly-precipitation-Rainfall,Boston,United-States-of-America  
Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. *Computing in Science & Engineering, 9*(3), 90-95. 10.1109/MCSE.2007.55  
Meher, S. (2023). *Boston Weather 2013-2023*. Kaggle. https://www.kaggle.com/datasets/swaroopmeher/boston-weather-2013-2023  
The pandas development team. (2026). pandas-dev/pandas: Pandas (v3.0.3). Zenodo. https://doi.org/10.5281/zenodo.20127038  
Waskom, M. L., (2021). seaborn: statistical data visualization. *Journal of Open Source Software, 6*(60), 3021, https://doi.org/10.21105/joss.03021

## About the Author
Hi! My name is Emma Bowen and I am an online master's student studying Computational Life Science at Arizona State University, expected to graduate Fall 2026. Previously, I recieved my B.S. from Oregon State University majoring in Biology and minoring in Chemistry. I then worked for two years for Kforce Inc at Hewlett-Packard in Corvallis, Oregon as a Chemical Technician V for an ink development laboratory. I have a passion for biology, genomics, bioinformatics, and data analysis/visualization. This passion inspired me to continue my education and dive deeper into computational life sciences. As I have developed new skills through my master's program, I began to complete my own personal data analysis, visualization, and pipeline projects that are presented here on my GitHub. I have branched out and learned new programming languages and querying, including R, Python, Linux CLI, and SQL. If you would like to contact me, here is my information:  
email: emmabowen05@gmail.com  
linkedin: https://www.linkedin.com/in/emma-bowen-0628aa274/  
