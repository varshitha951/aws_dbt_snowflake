Overview

This project implements an end-to-end data engineering pipeline using AWS, Snowflake, and dbt to transform raw Airbnb data into analytics-ready datasets.

Tech Stack

AWS S3 – Data storage

Snowflake – Cloud data warehouse

dbt – Data transformation and modeling

SQL & Jinja – Data processing and reusable logic

Git & GitHub – Version control

Project Workflow

Load raw Airbnb data into AWS S3.

Ingest data into Snowflake.

Transform data using dbt.

Organize data into Bronze, Silver, and Gold layers.

Implement incremental models and snapshots.

Create fact models and a One Big Table (OBT) for analytics.

Key Features

Medallion architecture

Incremental data loading

Reusable dbt macros

Historical data tracking using snapshots

Fact and dimension modeling
