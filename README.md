##  Overview
Built an end-to-end data engineering pipeline using **AWS, Snowflake, and dbt** to transform raw Airbnb data into analytics-ready datasets.

##  Tech Stack
- **AWS S3:** Stores raw Airbnb datasets.
- **Snowflake:** Loads and stores data in a cloud data warehouse.
- **dbt:** Transforms raw data into structured, analytics-ready models.
- **SQL & Jinja:** Build queries and reusable transformation logic.
- **Git & GitHub:** Manage version control and project code.

##  Project Workflow
1. Store raw Airbnb data in AWS S3.
2. Load the data into Snowflake.
3. Transform data using dbt models.
4. Organize datasets into Bronze, Silver, and Gold layers.
5. Implement incremental models and snapshots to manage data updates and historical changes.
6. Build fact models and a One Big Table (OBT) for analytics.

##  Key Features
- Medallion architecture (Bronze, Silver, and Gold).
- Incremental data loading.
- Reusable dbt macros using Jinja.
- Historical data tracking with dbt snapshots.
- Fact and dimension modeling.


