# airDelay

## Overview
The **airDelay** package provides tools for cleaning, analyzing, and visualizing airline delay data. It is designed for students and analysts who want an efficient way to explore delay patterns and trends.

## Functions

- `clean_delay_data()`  
  Cleans and prepares airline delay datasets.

- `summarize_delays()`  
  Calculates average delay by group (e.g., airline or time).

- `detect_delay_outliers()`  
  Identifies outliers using the Tukey method.

- `plot_delay_trends()`  
  Visualizes delay trends over time.

## Installation

```r
# Install from GitHub (if devtools installed)
devtools::install_github("mandion928/airDelay")
```

## Design Notes

The **airDelay** package does not currently define S3 or S4 classes.
Instead, I've opted to use standard exported R functions that operate on data frames. 
This design is works because the package focuses on tasks such as
data cleaning, summarization, outlier detection, and visualization.
