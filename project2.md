# Project 2
A data pipeline with several modular components, including but not limited to: 
- [ ] Java jar which:
  - [ ] Pulls data from a csv/json file on AWS S3
  - [ ] Defines Spark SQL actions on that data
  - [ ] Submits the Spark job to a cluster
- [ ] Apache Spark cluster with either:
  - [ ] Amazon EMR
  - [ ] Stand-alone cluster on AWS EC2
- [ ] Java jar which:
  - [ ] Reads query results/logs from AWS S3
  - [ ] Stores them on a SQL RDBMS

The pipeline is intended to be several applications which run in succession, taking a datasource from an S3 and deploying a Spark job on a cluster for analysis before saving the results in a SQL database. Some recommendations for organizing and extending the project:
- [ ] Use a Maven multi-module in a single Git repository
- [ ] Create an automation script or tool to kick-off the entire pipeline
- [ ] Create a program to pull or create data and store to AWS S3 before the pipeline runs
- [ ] Create a simple CLI or HTTP based analysis tool to query the SQL database

## Features
- [ ] Documentation
- [ ] Unit testing
- [ ] Logging
- [ ] Batch Processing
- [ ] Multi-module pipeline
- [ ] Cloud Services: S3
- [ ] Spark jobs run on a cluster
- [ ] SQL Data Persistance

## Tech Stack
- [ ] JavaSE 8:
  - [ ] Functional Programming
  - [ ] Streams
- [ ] Apache Spark SQL
- [ ] Maven 3
- [ ] JUnit 5
- [ ] Amazon Web Services:
  - [ ] S3
  - [ ] EMR
- [ ] Git SCM (on GitHub)

## Presentation
- [ ] 3-5 minute slide deck
- [ ] 5-10 minute live demonstration