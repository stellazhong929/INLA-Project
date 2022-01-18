# INLA-Project
Estimate the risk of Breast Cancer in females in North Carolina, USA, using the `R-INLA` package

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Methods](#methods)

## General info
Deidentified death records from the National Center for Health Statistics (NCHS) and population counts from the Census Bureau, the NCHS and the Human Mortality Database were used. Deaths and population were tabulated by county, year and cause. For this project, we only extract th death records of `Breast Cancer` an year between `2007 to 2014`. We also combine the conty-level information such a population density on age-groups, levels of education, race/ethnicity and othe socieconomic statu from data provide by [American Community Survy](https://www.census.gov/programs-surveys/acs).

## Technologies
Project is created with:
 - R Studio version:4.1.2

## Methods
Some highlights: 
  - Drawing county-level map for mortality rate of breast cancer and percentage change between 2007 to 2014
  - Performing feature selection using LASSO and Elastic Net
  - Fitting generalized mix effect models with spatial random effects for longitudinal, count data
  - Mapping relative risk and exceedence probabilities using `R-Leaflet`

## Project Status
Project is *still in progress*; Will be finished before March.2022

## Acknowledgements
Project idea is originate from the paper: [Trends and Patterns of Disparities in Cancer Mortality Among US Counties, 1980-2014](https://jamanetwork.com/journals/jama/fullarticle/2598772?utm_campaign=articlePDF&utm_medium=articlePDFlink&utm_source=articlePDF&utm_content=jama.2016.20324)
