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
