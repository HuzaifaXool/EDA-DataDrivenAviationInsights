# EDA-DataDrivenAviationInsights
Aviation Accidents Analysis

## Overview
This repository contains data-driven insights into aviation accidents based on an extensive dataset. It conducts an analysis of factors that cause such accidents, ranging from weather conditions to aircraft types and operational phases.

## Dataset
The dataset used for this analysis is based on records of aviation accidents, which are 88,889 in number and span across 31 columns. Data includes accident dates, locations, injury severity, damage to aircraft, and more.

## Cleaning of the Data
According to this document, the data cleaning methods applied were:
- Imputation: Mean imputation in numerical fields and mode imputation in categorical fields
- Outlier detection using Z-scores.
Data Visualization techniques, like box plots to understand distributions and identify anomalies.

## Key Findings
- **Accident Conditions**: Most accidents occur under VMC conditions and during the phases of landing.
- **Location Insights**: Anchorage, AK comes out as the location heading the accident count list.
- **Aircraft Analysis**: Flight Model No. 152 has a remarkably high probability of accidents.
- **Survival Rates**: The fatality rate goes down as the number of engines increases, hence demonstrating better survival rates with aircraft that have 3 through 8 engines.
- **Injury Analysis**: New Delhi has recorded the highest count of injuries during these accidents. Substantial damage to the aircraft was the common classification in most cases.

## Visualizations
The repository includes graphs visualizing data like the following:
- Accident count per airport
- Injury counts across various locations
- Correlation studies between different factors

## Technologies Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Seaborn and Matplotlib**: For data visualization.
- **SciPy**: For statistical analysis.
