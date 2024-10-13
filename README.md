# ETL_Workflow
# Extract:
1. There are three different file formats(CSV,JSON,XML) from where the data is extracted and stored in a single DataFrame.
# Transform:
2. The height is converted from inches to meteres and weight is converted from lbs to kgs
# Load:
3. Finally the Transformed data is loaded into an output CSV file.
# Logging:
Each of the phase is logged with the function along with the timestamp and stored in etl_process.log file
