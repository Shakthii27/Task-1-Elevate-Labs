## Changes made to the csv file 
- Missing values were identified in important columns such as director, cast, country, and rating, and these were filled with appropriate placeholder values like Unknown or Not Available.  
- Duplicate rows were removed to ensure data consistency.  
- Text values such as type and country names were standardized by trimming extra spaces and converting them into a uniform title format.
- The date_added column was converted into a consistent datetime format for proper time-based analysis.
- Column headers were also cleaned by converting them to lowercase and replacing spaces with underscores.
- Finally, data types such as release_year were corrected to integer format.
- The cleaned dataset was saved as netflix_cleaned.csv.  
