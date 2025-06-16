# COVID-19 Data Analysis

This project presents an analysis of global and U.S. COVID-19 case and death data using R. The data was sourced from the Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) GitHub repository. This work follows the data cleaning, wrangling, and visualization procedures covered in class.

## Contents

- `COVID-19 Report.Rmd`: R Markdown file used for data cleaning, analysis, visualization, and modeling.
- `covid19_report.html`: Rendered HTML version of the report.
- `README.md`: Overview of the project and access link.

## Live Report

[View the COVID-19 Report](https://raycirko.github.io/covid19-analysis/covid19_report.html)

## Data Source

- Johns Hopkins CSSE COVID-19 Data: https://github.com/CSSEGISandData/COVID-19

## Summary

The analysis includes:

- Data cleaning and reshaping using `tidyverse`
- Aggregation of global and U.S. COVID-19 statistics
- Time-series visualizations of confirmed cases and deaths
- Modeling of deaths per thousand as a function of cases per thousand
- Identification of new daily cases and deaths over time

## Bias and Limitations

- Time lags and underreporting may distort case or death totals, especially early in the pandemic.
- The decision to analyze aggregate cases and deaths excludes other health outcomes such as long COVID, hospitalization rates, or recovery times.
- Cross-country comparisons can be affected by differences in reporting standards, population testing coverage, and healthcare access.
- The type of variables chosen (e.g., cases and deaths) may overlook important social, economic, or systemic factors influencing the pandemic’s impact.
