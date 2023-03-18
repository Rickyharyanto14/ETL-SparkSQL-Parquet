# ETL SparkSQL Parquet

## :notebook: Library
1. import pyspark
2. from pyspark.sql import SparkSession
3. from pyspark.sql import Row

## :dart: Goals
Create an ETL pipeline using Spark SQL with the following conditions:
1. Extract process: read data (input) into csv and make it into a dataframe
2. Transforms process: filter data where the PUlocationID and DOlocationID fields cannot be empty and pickup_datetime starts from 1 Jan 2021 to 10 Jan 2021
3. Load Process: write data after transform process to parquet and json files
