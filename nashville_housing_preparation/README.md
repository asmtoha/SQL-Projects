# Nashville Housing Market Data Preparation

This project demonstrates comprehensive data cleaning and preparation techniques for Nashville housing market data.

## Project Overview

The project focuses on cleaning and standardizing housing data through various SQL techniques and transformations to prepare it for market analysis.

## Data Cleaning Steps

### 1. Date Standardization
- Converting sale dates to consistent format
- Creating new standardized date columns
- Handling date format inconsistencies

### 2. Address Cleaning and Standardization
- Populating missing property addresses
- Splitting addresses into components:
  - Street address
  - City
  - State
- Standardizing address formats
- Handling address inconsistencies

### 3. Value Standardization
- Converting 'Y/N' to 'Yes/No' in SoldAsVacant field
- Ensuring consistent value formats
- Handling special cases and exceptions

### 4. Data Deduplication
- Identifying duplicate records
- Using ROW_NUMBER() for duplicate detection
- Removing redundant entries
- Maintaining data integrity

### 5. Column Management
- Removing unused columns
- Organizing data structure
- Optimizing table layout
- Ensuring data consistency

## Technical Implementation

### Data Source
- `nashville_housing_data.xlsx`: Original housing market data

### SQL Techniques Used
- String manipulation functions
- Table self-joins
- Common Table Expressions (CTEs)
- Window functions
- Data type conversions
- Table alterations
- Data validation queries

### Key SQL Features
1. Data Cleaning Procedures
2. Data Transformation
3. Quality Checks
4. Structure Optimization
5. Data Integrity Maintenance

## Workflow
1. Initial Data Assessment
2. Data Cleaning
3. Data Transformation
4. Quality Verification
5. Final Data Preparation 