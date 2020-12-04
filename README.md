# CareSet Tools to import COVID Hospital Capacity PUF into MySQL

This repo is a simple php script that wraps the MySQL code needed to import csv files from the HHS Protect database PUF release on Facility-level Hospital capacity data.

This is a command line php script that needs to have database credentials in the util/db.yaml file to work.

Then the usage of the command is: 
```
> php standalone_covid_data_importer.php <covid_csv_file_name> <db_to_import_to> <table_to_import_to> 
```
