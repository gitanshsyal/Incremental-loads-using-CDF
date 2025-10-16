# Incremental-loads-using-CDF
This project demonstrates how to implement incremental data loads using Delta Lake Change Data Feed (CDF) in Azure Databricks.

Tech Stack
======================================================
Azure Databricks

Delta Lake with CDF

Azure Data Lake Gen2

PySpark Structured Streaming

Steps Followed
========================================================
The pipeline:

=> Creates a Delta table with CDF enabled.
=> Loads source files from Azure Data Lake Gen2.
=>Merges the new data into the Delta table (insert/update).
=>Streams changes from the Delta table using CDF.
=>Writes the incremental changes to a target folder in Data Lake.
