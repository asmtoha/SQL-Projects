# Nashville Housing Data Cleaning

This project demonstrates comprehensive data cleaning techniques using Nashville housing data.

## Project Overview
The project focuses on cleaning and standardizing housing data through various SQL techniques and transformations.

## Data Cleaning Steps
1. Date Standardization
   - Converting sale dates to consistent format
   - Creating new standardized date columns

2. Address Cleaning
   - Populating missing property addresses
   - Splitting addresses into components (street, city, state)
   - Standardizing address formats

3. Value Standardization
   - Converting 'Y/N' to 'Yes/No' in SoldAsVacant field
   - Ensuring consistent value formats

4. Data Deduplication
   - Identifying duplicate records
   - Using ROW_NUMBER() for duplicate detection
   - Removing redundant entries

5. Column Management
   - Removing unused columns
   - Organizing data structure
   - Optimizing table layout

## Technical Implementation
- Uses various SQL techniques including:
  - String manipulation functions
  - Table self-joins
  - Common Table Expressions (CTEs)
  - Window functions
  - Data type conversions
  - Table alterations

## Data Source
- `Nashville Housing Data for Data Cleaning.xlsx`: Original housing data

## SQL Script
The main cleaning process is documented in `data_cleaning.sql`, which includes:
- Step-by-step data cleaning procedures
- Data transformation queries
- Table structure modifications
- Data quality checks 