
# Examining the Relationship Between Environmental Conditions and Marathon Performance in Male and Female Runners of Different Ages

## Background

Female and male runners of all ages test the limits of their endurance in marathons, but the weather on the day of the race is outside any participant’s control. Do these different groups of runners respond differently to challenging environmental conditions? This report explores the impact of weather and air quality on marathon performance in male and female runners of different ages. 

## Methods

This report examines marathon performance under different environmental conditions by female and male runners of different ages. Using the fastest single-age finishing time for male and female runners in five major marathons run annually over approximately two decades, performance is measured as the runner’s finishing time as a percent of the prior course record for his or her sex. The report investigates the relationship between this metric of performance, air quality index (AQI) measured as an average of seven parameters, and indices of weather to include Wet Bulb Globe Temperature, relative humidity, wind, and dew point. We used normalized difference in %CR for plotting in order to more clearly illustrate the differences in performance across age, sex, and environmental covariates. 

## Results

Key Findings:
- Marathon performance demonstrates a U-shaped relationship with age, more pronounced in female runners.
- Increased WBGT and wind speed generally slow down runners, with older and female runners experiencing greater impacts.
- Surprisingly, higher humidity levels appeared to slightly enhance performance, particularly among older athletes.
- Air quality impacts were more significant in male runners than in females.

[The full report can be found here](https://github.com/tomrannosaurus/marathon_project/blob/main/marathon_eda.pdf)


## Setup

- R Version: 4.3.1
- Package Versions:
   - tidyverse: 2.0.0
   - knitr: 1.45
   - kableExtra: 1.3.4
   - ggplot2: 3.4.3
   - naniar 1.0.0
   - visdat 0.6.0
   - car 3.1-2
   - lme4 1.1-34
   - ggpubr 0.6.0
   - outliers: 0.15
   - reshape2: 1.4.4
   - moments: 0.14.1
   - vcd: 1.4-12

## Files

- Report Quarto: marathon_eda.qmd
- Helper functions code: _helpers.R
- Tex files: column-commands.tex, float-setup.tex, geometry-settings.tex, table-packages.tex, title-settings.tex
- References file: references.bib
