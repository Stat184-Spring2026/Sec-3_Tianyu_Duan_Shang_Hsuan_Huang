# Flight Delay Analysis

This repository analyzes flight delays in the United States to understand the main causes of delays and whether flight distance affects total delay time.

## Overview

This project uses U.S. flight data to explore key factors contributing to flight delays. We focus on three main types of delays: carrier delay, weather delay, and NAS delay. Using R's visualization tools, we aim to identify patterns and relationships in the data.

Our goal is to determine which factors have the greatest impact on delays and whether flight distance plays a significant role.

### Interesting Insight (Optional)

One key insight from our analysis is that **carrier delay is the largest contributor to total flight delay**, suggesting that airline operations have a greater impact than external factors such as weather.

Below is an example visualization:
<img width="1366" height="1060" alt="d845451d-9b08-49d9-af90-f28c230637ec" src="https://github.com/user-attachments/assets/6cbed7b3-e94d-42ad-a4e6-77cb6d0cacce" />

## Data Sources and Acknowledgements

The dataset used in this project comes from U.S. flight data sources.

We acknowledge the use of:
- R programming language
- tidyverse package (dplyr, ggplot2)

## Current Plan

We plan to:
- Clean and prepare the dataset
- Combine multiple delay variables into a total delay metric
- Create visualizations to identify patterns
- Interpret findings and explain the causes of flight delays

## Repo Structure

- `report.qmd` → Main analysis report
- `T_ONTIME_REPORTING 2(1).csv` → Raw dataset
- `README.md` → Project description
- `plots/` → Saved visualization images

## Authors

- Shang-Hsuan Huang (sfh5800@psu.edu) 
- Tianyu Duan
