# Exploratory Data Analysis & Visualization
## Overview
This repository features four data analysis projects demonstrating the use of R and ggplot2 to uncover trends in diverse datasets. The analyses focus on data wrangling, visualization, and interpreting patterns in academic performance, urban transportation, and music history.

## Key Analyses
### 1. Academic Performance Factors (profs.csv)
Objective: Investigate variables influencing professor course evaluation scores.

Findings:

Language Fluency: Confirmed that native English speakers tend to receive higher evaluation scores on average.

Attractiveness: Found a negligible correlation between a professor's physical attractiveness and their evaluation score, debunking the "beauty premium" in this specific context.

Gender: Observed that male professors' scores were slightly more negatively skewed (more high scores) compared to female professors.

### 2. Urban Mobility Trends (bikeshare.csv & capmetro_UT.csv)
Objective: Analyze ridership patterns for bike-sharing systems and UT Austin bus routes.

Bike Sharing Findings:

Commuter Effect: Ridership peaks sharply at 8:00 AM and 5:00 PM on weekdays, confirming a strong correlation with standard working hours.

Weather Sensitivity: Ridership consistently decreases as weather conditions worsen (e.g., rain, snow), though the necessity of commuting on weekdays partially mitigates this drop compared to weekends.

Bus Ridership Findings:

Seasonal Dips: Identified lower ridership in September (likely due to semester startup adjustment) and November (attributed to Fall Break).

Temperature Independence: Scatterplots revealed no significant relationship between ambient temperature and bus boarding frequency.

### 3. Music Industry Trends (billboard.csv)
Objective: Track the evolution of song popularity and musical diversity over six decades.

Findings:

Musical Diversity: The number of unique songs appearing on the charts declined steadily from 1965 to 2000, suggesting a period of chart stagnation, before rebounding dramatically in the late 2000s.

"Ten-Week Hits": Identified 19 legendary artists (including Elton John, Madonna, and Kenny Chesney) who achieved 30 or more songs that stayed on the Billboard Top 100 for at least 10 weeks.

## Tech Stack
Language: R

Libraries: tidyverse, ggplot2, dplyr, kableExtra

Techniques: Data Wrangling, Faceted Plotting, Time-Series Analysis, Correlation Analysis
