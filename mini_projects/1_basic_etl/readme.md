## Basic ETL Pipeline (Student Marks)
This mini project demonstrates a simple ETL (Extract, Transform, Load) process using python and pandas.

### ETL Steps
1. Extract
- Load raw data from raw_marks.csv.

2. Transform
- Convert text and missing values to numeric.
- Correct invalid marks (between 0–100).
- Fix semester format and remove duplicates.
- Add new columns: Total and Average.

3. Load
- Save the cleaned data to cleaned_marks.csv.