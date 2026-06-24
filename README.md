

# Power BI Sales Data Preparation Project

## Project Overview
This project demonstrates basic data preparation and transformation in Power BI using a sales dataset. The workflow includes importing data, reviewing structure, cleaning records, merging and appending tables, pivoting/unpivoting data, creating relationships, and reviewing the final model.

## Tools Used
- Power BI Desktop
- Power Query Editor
- Excel Dataset

## Dataset
The dataset contains sales-related information including:
- Date
- Chain
- Country
- Category
- Total Units
- Sale Price
- Cost Price

## Key Steps Completed
1. Imported Excel dataset into Power BI
2. Reviewed data structure in Power Query Editor
3. Removed duplicate records
4. Checked missing values and corrected data types
5. Merged main dataset with a country-region lookup table
6. Appended an additional referenced dataset
7. Practiced pivoting and unpivoting columns
8. Created a relationship between Dataset and Country_table
9. Reviewed final data in Power BI

## Transformations Performed
- Removed duplicate rows
- Validated date and numeric formats
- Created Country_table with Region information
- Merged tables using Country as the common key
- Appended a referenced dataset
- Converted price columns using unpivot and pivot operations

## Data Model
A one-to-many relationship was created between:

Country_table[Country] → Dataset[Country]

## Project Outcome
The project shows how Power BI can be used to clean, transform, combine, and model data before analysis and reporting.

## Files Included
- Power BI file (.pbix)
- Excel dataset
- Screenshots of transformation steps
