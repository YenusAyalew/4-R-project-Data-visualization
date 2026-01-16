# Project 4 - Data Visualization

This is my fourth R project, where I focused on exploring and visualizing real-world datasets. My goal was to create plots that are clear, informative, and visually engaging.

## Task 1 — Child Mortality vs Health Expenditure (2019)

For this task, I used data from [Our World in Data](https://ourworldindata.org/) to explore the relationship between child mortality rates and health expenditure per capita for the year 2019.

I created a bubble scatter plot with:

- **X-axis**: Health expenditure per capita (PPP, log scale)
- **Y-axis**: Child mortality (deaths per 100 live births, log scale)
- **Bubble size**: Population (billions)
- **Bubble color**: WHO region

I highlighted a set of countries to make the plot more readable and insightful.

The dataset I used is located in:

`child-mortality-vs-health-expenditure Logarithmic scale/child-mortality-vs-health-expenditure 2019.csv`

## Task 2 — Principles of Good Data Visualization

For this task, I illustrated a visualization principle I learned: **always show uncertainty**.

I used a small dataset of class mean scores and standard deviations to create a two-panel plot:

- **Left panel**: Shows only mean scores (misleading because it hides variability)
- **Right panel**: Shows mean scores with error bars representing standard deviation, making variability clear

This task helped me understand why visualizing uncertainty is crucial for honest and informative plots.

I saved the output plot as:

`show_variability_error_bars.png`

## Key Learnings

Through this project, I:

- Improved my skills in `ggplot2` and `tidyverse` for creating informative plots
- Learned to use log scales, highlight important data points, and represent variability in my data
- Applied principles of good visualization to communicate data clearly and honestly
