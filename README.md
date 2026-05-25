# Crime Data Analysis (R Markdown Project)

## Overview

This project analyzes multiple types of crime data in the United States using R and R Markdown. The goal is to explore trends over time and across regions for different crime categories, including hate crimes, cargo theft, human trafficking, and assaults.

The analysis includes data cleaning, filtering, aggregation, and visualization to identify patterns across years and regions.

---

## Datasets Used

The project uses four datasets:

- Hate Crime Data
- Cargo Theft Data
- Human Trafficking Data
- Assault Law Data

Each dataset contains yearly crime records and state-level information.
Note: Most datasets used in this project are too large to be uploaded to GitHub. Only the Human Trafficking dataset is included in this repository. The remaining datasets must be downloaded separately and placed in the same local directory used in the R Markdown file.

---

## Tools & Libraries

This project was built using R and the following packages:

- dplyr
- ggplot2
- tidyr
- readr

---

## Project Steps

### 1. Data Import
All datasets were loaded into R from CSV files.

### 2. Data Cleaning
- Converted year columns to numeric format
- Filtered data for years 2015 and later
- Handled missing values where needed

### 3. Exploratory Data Analysis
- Aggregated crime counts by year
- Aggregated crime counts by state
- Compared crime trends across categories

### 4. Visualization
Created multiple plots including:
- Crime trends over time
- Crime comparison by type
- Regional breakdowns of crime patterns

---

## Key Insights

- Crime types show different trends over time
- Certain crime categories fluctuate significantly year-to-year
- Regional differences suggest geographic variation in crime patterns

---

## How to Run This Project

### 1. Install required packages:
```r
install.packages(c("dplyr", "ggplot2", "tidyr", "readr"))

## Author Jeremy Granflaten
