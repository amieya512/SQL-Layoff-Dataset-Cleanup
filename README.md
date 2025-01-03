# SQL Layoff Dataset Cleanup

## Project Overview
This project involves cleaning a layoff dataset using SQL techniques. The goal was to prepare the data for analysis by handling issues such as missing values, duplicates, and standardizing data formats.

## Dataset
- **Original File:** layoffs.csv (raw dataset)
- **Cleaned File:** layoffs_cleaned.csv (after data transformation)
- **Source:** Layoff data sourced from Alex The Analyst's GitHub repository.

## Objectives
- Identify and remove duplicates
- Handle null values effectively by direct replacements and filtering
- Standardize date and text formatting
- Perform data normalization and restructuring

## Tools Used
- SQL (Local instance)
- Dataset: Layoff data in CSV format

## Key Steps
1. **Data Import:** Loaded the `layoffs.csv` file into the database.
2. **Data Cleaning Steps:**
   - Removed duplicate entries using `DISTINCT`.
   - Handled null values using direct replacements (`UPDATE SET column = value WHERE column IS NULL`).
   - Standardized date formats using `DATE_FORMAT()`.
   - Normalized company names and job roles using `TRIM()` and `LOWER()` functions.
3. **Export Cleaned Data:** Exported the transformed data into `layoffs_cleaned.csv` for further analysis.

## Files in This Repository
- `SQL Layoff Dataset Cleanup.sql`: Contains the SQL queries used for cleaning the dataset.
- `layoffs.csv`: The original dataset used for this project.
- `layoffs_cleaned.csv`: The cleaned and transformed version of the dataset.
- `README.md`: This document explaining the project.

## How to Use
1. Import the `layoffs.csv` into your SQL environment.
2. Run the queries provided in `SQL Layoff Dataset Cleanup.sql`.
3. Review the `layoffs_cleaned.csv` for the cleaned dataset.

## Skills Demonstrated
- SQL querying and data transformation
- Handling missing data and duplicates
- Data standardization and cleaning principles



