# Exploratory Data Analysis (EDA)

## Overview

This project provides a framework for conducting exploratory data analysis (EDA) on applicant and recruitment datasets. The script examines distributions, identifies missing or unusual values, explores relationships between variables, and prepares data for further statistical analysis or reporting.

## Features

* Generates frequency distributions for categorical variables
* Creates bar charts, histograms, boxplots, and scatterplots
* Identifies common applicant characteristics and recruitment trends
* Detects outliers and unusual values
* Cleans and standardizes numeric fields stored as text
* Performs basic correlation analysis between numeric variables
* Filters and examines small, medium, and large applicant subgroups
* Supports data quality assessment and preprocessing

## Packages Used

* `tidyverse`
* `lattice`

## Input

* `Job_Applicants.csv`

## Analysis Components

### Categorical Variables

The script analyzes frequency distributions for:

* Job titles
* Certification areas
* Civil service test status
* School districts
* Employment interests
* Position types
* Law conviction responses
* Applicant locations
* Recruitment sources

### Continuous Variables

The script evaluates numeric variables using:

* Histograms
* Summary statistics
* Variance calculations
* Correlation testing

Examples include:

* Years of experience
* GPA
* Candidate counts
* Salary information

### Data Quality Checks

The script includes methods for:

* Detecting outliers using boxplots
* Replacing unusual values with missing values (`NA`)
* Parsing numeric values from text fields
* Standardizing inconsistent salary descriptions

### Recruitment Insights

The analysis can be used to:

* Identify the most and least popular job postings
* Evaluate recruitment source effectiveness
* Understand applicant demographics and qualifications
* Explore relationships between candidate volume and compensation

## Output

The script produces summary statistics, frequency tables, visualizations, and cleaned variables that support recruitment analytics, reporting, dashboard development, and further statistical modeling.

## Potential Applications

* Human resources analytics
* Recruitment pipeline evaluation
* Applicant tracking system (ATS) reporting
* Workforce planning
* Educational staffing analysis
* Data preprocessing for machine learning and predictive modeling
