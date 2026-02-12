Lab 3: Exploratory Data Analysis (EDA)

This repository contains my solution for Lab 3 in the ARTI308 Machine Learning course.

The objective of this lab is to apply Exploratory Data Analysis (EDA) techniques to a dataset of my choice.

---

## Dataset Description

The dataset used in this lab is a COVID-19 daily records dataset at the county level in the United States.

Each row represents the reported COVID-19 statistics for a specific county on a specific date.

The dataset contains the following main columns:

- date: The reporting date
- county: County name
- state: State name
- fips: County FIPS code
- cases: Total cumulative confirmed cases
- deaths: Total cumulative deaths
- daily_cases: New cases reported on that day
- daily_deaths: New deaths reported on that day
- day_of_week: Day of the week (encoded as a number)
- is_weekend: Indicator showing whether the day is a weekend (1) or not (0)

---

## EDA Tasks Performed

The following exploratory data analysis steps were applied:

- Checking dataset shape (rows and columns)
- Checking missing values
- Checking duplicate records
- Data type inspection and date conversion
- Descriptive statistics
- Univariate analysis of daily cases
- Relationship analysis between daily cases and daily deaths
- Correlation analysis among COVID-related numerical variables
- Time-based analysis of daily cases
- Noise reduction using a 7-day moving average

---

## Files in this repository

- ARTI308_Lab3_COVID.ipynb  
- IntegratedData.csv
