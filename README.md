# DRC Ebola Surveillance Data Analysis

Analysis of the 2026 DRC Ebola surveillance dataset, focusing on
outbreak progression, data quality, interpolation, growth rates,
and case fatality.

## Objectives

This project analyses the DRC Ebola surveillance data to:

- Aggregate provincial data into a national daily series
- Assess the number of affected provinces, cases, and deaths
- Investigate missing reporting dates
- Interpolate missing observations
- Estimate cumulative case and death thresholds
- Calculate outbreak growth rates
- Analyse the relationship between cumulative cases and deaths
- Discuss the implications of interpolating surveillance data

## Methods

The analysis uses Python and includes:

- Pandas
- NumPy
- Matplotlib
- SciPy
- Data cleaning and aggregation
- Time-series interpolation
- Growth-rate analysis
- Epidemiological descriptive analysis

The complete analysis is available in:

[`ebola_analysis.ipynb`](ebola_analysis.ipynb)
