# ETL Pipeline Project

 ## Project Overview

This project is a Python-based ETL (Extract, Transform, Load) pipeline that extracts data from different file formats (CSV, JSON, XML), transforms it, and loads it into a CSV file.

#### Extract: Reads CSV, JSON, and XML files.

#### Transform:

- Converts height from inches to meters (rounded to 2 decimal places).

- Converts weight from pounds to kilograms (rounded to 2 decimal places).

#### Load: Saves the transformed data into transformed_data.csv.

#### Logging: Records the ETL process steps in log_file.txt

##  Data Source
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0221EN-SkillsNetwork/labs/module%206/Lab%20-%20Extract%20Transform%20Load/data/source.zip

## Libraries Used

- pandas → Data manipulation

- zipfile → Extract ZIP files

- urllib → Download files from the internet

- glob → File pattern matching

- datetime → Timestamps for logging

- os → File operations
