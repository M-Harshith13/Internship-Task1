# Internship-Task1
Data Cleaning & Preprocessing Summary – Netflix Dataset

The Netflix Movies and TV Shows dataset was cleaned and prepared for analysis using Python (Pandas).

Steps Performed:

Checked for missing values using .isnull().sum().

Replaced missing values in:

director → "Unknown"

cast → "Not Available"

country → "Not Specified"

rating → "Not Rated"

Removed rows with missing critical fields such as date_added and duration.

Removed duplicate records using .drop_duplicates().

Standardized text columns (trimmed spaces, applied consistent formatting).

Converted date_added to a consistent datetime format (dd-mm-yyyy).

Renamed column headers to lowercase and replaced spaces with underscores.

Ensured correct data types (e.g., release_year as integer).

Result:

The dataset is now clean, consistent, and ready for exploratory data analysis or modeling.
