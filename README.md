
This repository contains a cleaned version of the Netflix Movies and TV Shows dataset.

 Summary of Changes

- Removed duplicate rows
- Handled missing values:
  - `director`: Filled with "Unknown"
  - `cast`: Filled with "Not Available"
  - `country`: Filled with "Unknown"
  - `rating`: Filled with "Not Rated"
  - `date_added`: Filled with "Missing" if blank
- Standardized date format in `date_added` to `dd-mm-yyyy`
- Standardized text fields
- Renamed all columns to lowercase with underscores (e.g., `show_id`, `date_added`)

Files include:
 `netflix_cleaned.xlsx`
  `README.md`

Tools Used: Microsoft Excel, documentation via Notepad

Author: Gayatri Sukhe  
Date: 23 june 2025