## Home Sales Analysis with PySpark

**Project Overview**:
This project utilizes PySpark to perform various analyses on a dataset of home sales. The dataset includes information about properties such as the number of bedrooms, bathrooms, square footage, year built, view rating, and more. The project explores different aspects of the data, including average home prices based on various criteria.

**Key Features**:
1. Data Ingestion:

2. The dataset is ingested from a CSV file hosted on an AWS S3 bucket.
Data Transformation:

3. Data is transformed and queried using SQL within PySpark.
Caching:

a. The home_sales temporary table is cached to improve query performance.
Performance Comparison:

b. Runtime comparison between cached and uncached data queries.
Data is partitioned by date_built and stored in Parquet format for optimized querying.


**Queries**:

Average price of homes based on different criteria such as:
Number of bedrooms and bathrooms.
Number of floors and square footage.
View rating with a price threshold.
Steps to Run
Setup Spark Environment:

Ensure Spark and necessary dependencies are installed and configured.
**Run Analysis**:

Execute the provided PySpark scripts or Jupyter notebook to perform the analysis.

**Caching & Uncaching**:

Observe the impact of caching on query performance.
Uncache tables when done to free up resources.
Parquet Operations:

Partition data by date_built and save it as Parquet files.
Run queries on the Parquet data and compare performance.


## Requirements
Python 3.x
PySpark
Java 11

## How to Use
Clone the repository.
Set up the Spark environment.
Execute the scripts in a PySpark environment or Jupyter notebook.
Modify queries as needed to explore different aspects of the dataset.
