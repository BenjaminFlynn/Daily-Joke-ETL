# Daily-Joke-ETL
This ETL takes extracts a daily joke from a joke API, transforms it into a readable text, and then loads it into a Snowflake data warehouse.  After that happens the joke it then emailed to you.  This uses Apache Airflow as the orchestrator and is ran on a Docker image.
