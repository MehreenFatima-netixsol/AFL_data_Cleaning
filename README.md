#  AFL Player Data Cleaning, Validation & Merging

## Overview

This project focuses on assessing, cleaning, validating, and merging two AFL datasets to create a reliable, analysis-ready dataset. The workflow follows standard data preprocessing practices commonly used in data analytics projects, ensuring data quality before further analysis or visualization.

The project includes comprehensive data cleaning, validation checks, documentation of cleaning decisions, and merging of player information with seasonal performance statistics.

---

## Objectives

- Assess the quality of two AFL datasets.
- Identify and resolve data quality issues.
- Clean and standardize the datasets.
- Validate the cleaned data.
- Merge both datasets using a common key (`player_id`).
- Produce a final dataset suitable for analysis.
- Document every cleaning decision throughout the process.

---

## Datasets

### 1. Players Information Dataset
Contains player demographic and profile information, including identifiers and personal details.

### 2. Seasonal Statistics Dataset
Contains yearly player performance statistics across AFL seasons.

---

## Data Cleaning Tasks Performed

The following preprocessing steps were completed:

- Removed duplicate records
- Identified and handled missing values
- Standardized column names
- Removed leading and trailing whitespace
- Corrected inconsistent text formatting
- Converted columns to appropriate data types
- Validated numerical values
- Verified primary key consistency
- Merged datasets using `player_id`
- Checked for unmatched player IDs after merging

---

## Validation Checks

The notebook includes validation reports covering:

- Dataset row counts
- Remaining missing values
- Duplicate record verification
- Data type validation
- Merge validation
- Identification of unmatched `player_id` values

---

## Files Included

```text
AFL_Data_Cleaning/
│
├── players_info.csv
├── seasonal_stats.csv
├── cleaned_players_info.csv
├── cleaned_seasonal_stats.csv
├── merged_players.csv
├── AFL_Data_Cleaning.ipynb
└── README.md
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Workflow

1. Load datasets
2. Perform initial data assessment
3. Identify data quality issues
4. Clean and standardize both datasets
5. Validate cleaned datasets
6. Merge datasets on `player_id`
7. Export cleaned datasets
8. Generate validation report
9. Document cleaning log and observations

---

## Project Deliverables

- ✅ Data Quality Assessment Report
- ✅ Cleaned Players Information Dataset
- ✅ Cleaned Seasonal Statistics Dataset
- ✅ Merged Analysis-Ready Dataset
- ✅ Cleaning Log
- ✅ Validation Report
- ✅ Jupyter Notebook
- ✅ Observations and Insights

---

## Observations

- Duplicate records were successfully identified and removed.
- Data consistency improved through standardization of text fields and column formats.
- Missing values were handled appropriately to maintain data integrity.
- All datasets were validated before merging.
- The final merged dataset is clean, consistent, and ready for exploratory data analysis or predictive modeling.


## Author

**Mehreen Fatima**
