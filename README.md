# da-task-1
# NETFLIX_DATA
DATA CLEANING

1. Task Overview
   The goal was to prepare the Netflix Movies and TV Shows for analysis by removing errors, standardizing values, and maintaining both raw and cleaned versions.

2. Tools Used
   Google Sheets (for data cleaning and formatting)
   Kaggle (for dataset source)

3. Files Delivered
   Raw_Data.xlsx → Original dataset imported into Google Sheets
   Cleaned_dataset.xlsx → Cleaned version of the dataset
   cleaned_dataset.csv → Exported cleaned data for analysis tools

4. Dataset Cleaning Steps Performed

 Step 1: Import CSV into Google Sheets
         The CSV file was imported using comma delimiter (,) so that each value was placed correctly into separate columns.
          First row was set as column headers.
 Step 2: Freeze Header & Apply Filters
         Top header row was frozen for easy navigation.
         Filters were applied to all columns for better data exploration.
 Step 3: Identify & Handle Missing Values
         Missing values were found using Filter → Blanks.
         Missing cells were highlighted using Conditional Formatting.
 Step 4: Detect & Remove Duplicates
         A backup sheet was created first.

Duplicates were checked using Data → Data cleanup → Remove duplicates based on show_id and title.

 Step 5: Standardize Text Fields
         Extra spaces removed using TRIM().

Text formatting applied:
    Titles, Names, Country → PROPER(TRIM())
    After cleaning, values were pasted as values only and original data replaced safely.

 Step 6: Validate and Fix Formats
         Dates were converted to valid date format.

Numeric fields (e.g., release_year) were checked to ensure only numbers existed.

5. Conclusion
   This data cleaning process helped in converting the raw Netflix dataset into a clean, consistent, and analysis-ready format while maintaining professional standards and         documentation practices.
