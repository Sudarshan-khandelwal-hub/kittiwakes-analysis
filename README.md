# Kittiwake Population Analysis Project

## Overview
This repository contains an analysis of kittiwake populations based on various datasets, including observational data, historical breeding patterns, physical measurements, and location-based information. The analysis was conducted as part of the MTHS4005 Applied Statistics coursework.

## Project Structure
- `MTHS4005_Coursework_20533986.pdf`: Comprehensive report detailing the analysis and findings
- `R_Program.Rmd`: R Markdown file containing all the code and analysis
- Datasets (required but not included in repository):
  - `Kittiwake_Observation_20533986.csv`
  - `Kittiwake_Historical_20533986.csv`
  - `Kittiwake_Measurement_20533986.csv`
  - `Kittiwake_Location_20533986.csv`

## Key Findings

### Problem
- Ornithologists needed to understand the complex factors affecting kittiwake populations
- Multiple datasets with different variables made comprehensive analysis challenging
- Uncertainty about whether population decline was site-dependent
- Lack of clear understanding about subspecies differences

### Solution
- Implemented multi-faceted statistical analysis using R
- Developed predictive models for breeding pairs
- Conducted comparative analysis between subspecies
- Applied both linear and logarithmic transformations
- Used advanced statistical methods (MANOVA, confidence intervals)

### Results
1. Population Dynamics:
   - Discovered site-dependent population decline, contrary to initial hypothesis
   - Estimated 45.5 breeding pairs for Site C in 2007
   - Established 80% confidence interval for dusk observations: [56.24, 60.91]

2. Environmental Impact:
   - Identified sandeel concentration and cliff height as critical factors
   - Developed predictive model with 90% confidence intervals
   - Log-transformed model showed superior predictive power (higher R-squared)

3. Subspecies Characteristics:
   - Found distinct physical characteristics between subspecies
   - Black-legged kittiwakes showed independent relationship between wingspan and culmen length
   - Red-legged kittiwakes exhibited dependent relationship

4. Practical Applications:
   - Created reliable prediction model for breeding pairs
   - Established framework for future population monitoring
   - Provided evidence-based insights for conservation strategies

## Analysis Components

### 1. Observation Data Analysis
- Exploratory analysis of kittiwake sightings
- Construction of 80% confidence intervals for mean dusk observations
- Visual representation through kernel density plots, histograms, and box plots

### 2. Historical Data Analysis
- Investigation of population decline across different sites
- Trend analysis for breeding pairs
- Interpolation for Site C breeding pairs in 2007

### 3. Measurement Data Analysis
- Comparison of physical characteristics between black-legged and red-legged kittiwakes
- Statistical analysis of wingspan, culmen length, and weight
- MANOVA analysis for subspecies differences

### 4. Location Data Analysis
- Linear modeling of breeding pairs
- Analysis of environmental factors affecting breeding populations
- Confidence interval predictions for specific site conditions

## Requirements
- R (version 4.0 or higher recommended)
- Required R packages:
  - ggplot2
  - dplyr
  - tidyr
  - broom

## Usage
1. Clone the repository
2. Place the required CSV datasets in the same directory as the R Markdown file
3. Open `R_Program.Rmd` in RStudio
4. Install required packages if not already installed:
```R
install.packages(c("ggplot2", "dplyr", "tidyr", "broom"))
```
5. Run the R Markdown file to reproduce the analysis

## Note
The datasets used in this analysis are not included in the repository. Please ensure you have the correct datasets with matching column names and formats to run the analysis.
