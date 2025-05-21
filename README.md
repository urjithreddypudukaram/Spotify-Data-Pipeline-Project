# Spotify Data Pipeline Project

### Introduction
In this Project, I built an ETL pipeline using Spotify API on AWS. The pipeline will retrieve data from the Spotify API, transform it to desired format, and load it into an AWS data store.

### Dataset / API
This API contains information about music artist, albums, and songs - [Spotify API](https://developer.spotify.com/documentation/web-api)

### Services Used
1. **Amazon S3 (Simple Storage Service):** Amazon S3 is a scalable object storage service used to store and retrieve any amount of data at any time. It is commonly used for data lakes, backups, and static website hosting.

2. **AWS Lambda:** Lambda is a serverless compute service that runs code in response to events without provisioning or managing servers. It automatically scales and is ideal for lightweight backend functions.

3. **Amazon CloudWatch:** CloudWatch monitors AWS resources and applications, collecting and tracking metrics, logs, and events. It helps in real-time monitoring and triggering alarms for automated actions.

4. **AWS Glue Crawler:** Glue Crawler automatically scans data in S3 (or other sources), infers the schema, and creates metadata tables in the Data Catalog. It simplifies data discovery and cataloging for ETL jobs.

5. **AWS Glue Data Catalog:** The Data Catalog is a centralized metadata repository to store table definitions, job metadata, and schema versions. It integrates with services like Athena, Redshift, and Glue jobs.

6. **Amazon Athena:** Athena is a serverless query service that allows you to run SQL queries directly on data stored in S3. It is highly effective for quick, ad hoc data analysis without setting up a database.

### Execution Flow
![Flow Diagram](https://github.com/urjithreddypudukaram/Spotify-Data-Pipeline-Project/blob/main/Execution%20Flow.jpg)
