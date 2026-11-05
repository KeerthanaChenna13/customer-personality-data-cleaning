# Customer Personality Analysis – Data Cleaning

## Project Overview
This project focuses on cleaning and preprocessing the Customer Personality Analysis dataset using Python and Pandas. The goal was to improve data quality and prepare the dataset for further analysis.

## Tools Used
- Python
- Google Colab
- Pandas

## Dataset
- Original dataset: 2,240 rows and 29 columns
- Cleaned dataset: 2,240 rows and 30 columns
- The additional column is `age`, calculated using 2014 as the reference year.

## Data Cleaning Steps
1. Checked the dataset structure and data types.
2. Identified 24 missing values in the `Income` column.
3. Replaced missing income values with the median.
4. Checked for duplicate records; none were found.
5. Converted `Dt_Customer` into datetime format.
6. Removed unnecessary leading and trailing spaces from text columns.
7. Identified unusual birth years and retained them for review.
8. Examined income outliers. Retained the seven high-income values and replaced the extreme value `666666` with the median income.
9. Created an `age` column using 2014 as the reference year.
10. Standardized column names and checked the final data types.

## Final Results
- Total records: 2,240
- Total columns: 30
- Missing values: 0
- Duplicate records: 0

## Deliverables
- Cleaned customer dataset (CSV)
- Python data-cleaning notebook
- Screenshots of important results
- This README file

## Conclusion
The dataset was cleaned and prepared for further analysis. The cleaned file can be used for Exploratory Data Analysis (EDA) and customer behaviour analysis.
