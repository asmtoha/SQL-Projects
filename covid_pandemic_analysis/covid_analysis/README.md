# COVID-19 Global Analysis

This project analyzes global COVID-19 data to understand the pandemic's impact and vaccination progress worldwide.

## Project Overview
The analysis focuses on:
- Global infection and death rates
- Country-specific analysis
- Vaccination progress tracking
- Population impact assessment

## Key Analyses
1. Death Rate Analysis
   - Total cases vs total deaths
   - Country-specific death rates
   - Global death percentage

2. Infection Rate Analysis
   - Population infection percentages
   - Highest infection rates by country
   - Continental analysis

3. Vaccination Analysis
   - Population vaccination progress
   - Rolling vaccination totals
   - Vaccination percentage calculations

## Technical Implementation
- Uses advanced SQL techniques including:
  - Common Table Expressions (CTEs)
  - Temporary tables
  - Window functions
  - Joins
  - Aggregations
  - Data type conversions

## Data Sources
- `CovidDeaths.xlsx`: Contains death and case data
- `CovidVaccinations.xlsx`: Contains vaccination data

## SQL Script
The main analysis is performed in `covid_analysis.sql`, which includes:
- Data exploration queries
- Statistical calculations
- Data preparation for visualization
- View creation for reporting 