# GSynergy
Downloaded all hierarchical and factual data from the drive to the local system.
Installed Azure Storage Explorer locally and configured Azure credentials.
Used Azure Storage Explorer to upload files into the ADLS container.
Created an Azure Resource Group.
Created an Azure Storage Account and set up a container within it.
Created an Azure Databricks notebook and connected it to the storage account using the access key.
Once Databricks was connected to the storage account, accessed files in the form of DataFrames using the mount location.
Performed various data validations, including:
Null checks for each column in all tables.
Uniqueness checks for primary keys.
Verification of data types for each column.
Designed a normalized table schema for efficient querying. Refer to the Normalized Tables Queries Python file for details.
Created all normalized tables along with a staging table for the fact table (transaction).
To compute mview_weekly_sales, joined the transaction table with the fiscal day table. For the complete implementation, refer to the Ingestion, Validation, and Transformation notebook.