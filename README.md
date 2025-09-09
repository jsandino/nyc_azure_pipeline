## NYC Payroll Data Pipeline

A Data Engineering project demonstrating the construction of a data pipeline using Microsoft Azure tools.


### Step 1: Prepare the Data Infrastructure

**Result**:

DataLakeGen2 that shows files are uploaded:

![](./screenshots/data_lake_dirs.png)

![](./screenshots/dirhistoryfiles.png)

![](./screenshots/dirpayrollfiles.png)

 5 tables created in SQL db:

![](./screenshots/sql-tables.png)

External table created in Synapse:

![](./screenshots/ext-table.png)


### Step 2: Create Linked Services

Linked Services page after successful creation:

![](./screenshots/link_services.png)


### Step 3: Create Datasets in Azure Data Factory

Created Datasets for files in Data Lake Gen2:

![](./screenshots/ds_agency_master.png)

![](./screenshots/ds_emp_master.png)

![](./screenshots/ds_payroll_2020.png)

![](./screenshots/ds_payroll_2021.png)

![](./screenshots/ds_title_master.png)

Created Datasets for SQL DB:

![](./screenshots/adf_datasets.png)


### Step 4: Create Data Flows

Dataflows in Data Factory:

![](./screenshots/adf_dataflows.png)


### Step 5: Data Aggregation and Parameterization

Aggregate dataflow in Data Factory:

![](./screenshots/dataflow_summary.png)


### Step 6: Pipeline Creation

Pipeline resource from Datafactory:

![](./screenshots/pipeline_design.png)


### Step 7: Trigger and Monitor Pipeline

Successful pipeline run:

![](./screenshots/pipeline_run.png)


### Step 8: Verify Pipeline run artifacts

Query from SQL DB summary table:

![](./screenshots/sql_summary.png)

dirstaging directory listing in Datalake that shows files saved after pipeline runs:

![](./screenshots/post_run_datalake.png)

Query from Synapse summary external table:

![](./screenshots/synapse_ext_table.png)


### Step 9: Connect your Project to Github

Published objects from Azure Data Factory:

![](./screenshots/github.com.png)