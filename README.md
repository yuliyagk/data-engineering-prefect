# Data Engineering with Prefect

This project is part of the Data Engineering Zoomcamp by DataTalksClub.

It demonstrates how to build and orchestrate data pipelines using Prefect, a modern workflow orchestration tool.


## Project Overview

The goal of this project is to design and automate a data pipeline that:

- Extracts data from external sources (NYC Taxi dataset)
- Transforms and cleans the data
- Loads the data into a storage system (local or cloud)
- Orchestrates the workflow using Prefect

## Tech Stack

- Python
- Prefect (workflow orchestration)
- Pandas (data transformation)
- Docker (optional)

## Workflow

The pipeline is implemented as a Prefect flow:

1. **Extract**  
   Download or fetch raw dataset

2. **Transform**  
   Clean data, handle missing values, format columns

3. **Load**  
   Store processed data (e.g. Parquet files / database)

4. **Orchestration**  
   Manage execution, retries, and scheduling with Prefect

## Example Use Case

This pipeline can be used for:

- Automated data ingestion
- Scheduled ETL jobs
- Data preparation for analytics or ML
