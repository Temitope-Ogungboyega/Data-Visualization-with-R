# Analysis of Dallas Police Data

This repository contains an RMarkdown analysis report examining the Dallas police dataset from The Center for Policing Equity. The report utilizes R and various data visualization libraries to explore demographics, trends, and potential biases in the Dallas policing data. 

## Contents

The repository includes the following files:

- [Dallas_Police_Analysis.Rmd](Data-Visualisation.Rmd): RMarkdown document containing the full data analysis report code and visualizations.


- [dallas_police_data.csv](dallas_police_data.csv): Raw Dallas police dataset imported and used for analysis.

- [Output html](Data-Visualisation-with-R.html.zip): Rendered HTML output of the RMarkdown report with analysis, plots, and findings.

## Report Contents

The RMarkdown report conducts an exploratory data analysis on the Dallas police data, including:

- Data cleaning, preprocessing, and wrangling using `tidyverse` and other R packages

- Visualizing the geographic distribution of incidents in Dallas using `leaflet`

- Analyzing trends in incidents over time by division, month, and hour using `ggplot2` 

- Examining demographics of officers and subjects involved in incidents

- Identifying potential racial disparities and biases in the data 

- Providing recommendations for improving policing practices based on the insights

## Usage Notes

The report is intended to be an example of using R and data visualization libraries to uncover insights from a police dataset. The raw data, code, and visualizations could serve as a template for conducting similar analyses on other datasets. 

To render the RMarkdown document, the required R packages need to be installed. The [Output html](Data-Visualisation-with-R.html.zip) file provides a pre-rendered version for quick reference.

## Key Findings

Some high-level findings from the analysis include:

- Significant racial disparities exist in the subjects involved in incidents 

- Incidents peak in the early evening hours between 5-8PM

- More experienced officers appear less likely to be involved in incidents

- Additional bias training may be needed to address potential discrimination
