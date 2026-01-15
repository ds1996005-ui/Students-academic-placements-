# Students-academic-placements-
Downloaded the Kaggle dataset (CSV format)
Ensured the file opened correctly in Excel with proper column headers and comma delimiters.
Set up the sheet for analysis
Used Freeze Panes to lock the header row.
Applied Filters to all columns for easy sorting, searching, and isolating values.
Identified missing values
Used filter dropdown → selected Blanks.
Highlighted empty cells with Conditional Formatting.
Decided whether to replace (e.g., “Unknown”), remove, or leave blank depending on the column context.
Detected duplicates
Created a backup sheet before making changes.
Used Data → Remove Duplicates on key columns (Student_ID or Name+Department+Graduation_Year).
Reviewed Excel’s summary of removed duplicates.
Standardized text fields
Inserted helper columns with formulas:
=TRIM(A2) → removed extra spaces.
=PROPER(A2) → converted to Proper Case.
=UPPER(A2) → converted to uppercase.
Copied cleaned values back into original columns using Paste Special → Values.
Validated formats
Checked date columns (converted to YYYY-MM-DD).
Cleaned numeric columns (removed symbols like $, %).
Standardized categorical values (used Data Validation lists to enforce consistency).
Created a Cleaned_Data sheet
Copied only the cleaned dataset into a new sheet named Cleaned_Data.
Kept raw data separate for traceability.
Added Data_Quality_Notes column
Documented issues and fixes, e.g.:
“Missing Placement_Status values filled with ‘Not Placed’”
“12 duplicate Student_IDs removed”
“Department names standardized to CSE/ECE/MECH”
Saved and exported final dataset
Saved as Cleaned_dataset.xlsx.
Exported as cleaned_dataset.csv for further analysis in Python, Power BI, or SQL.

🎯 Outcome
A clean, structured dataset ready for analysis.
A professional workflow that mirrors how analysts handle raw data.

Documentation of every decision (via Data_Quality_Notes) to show transparency and analytical thinking

