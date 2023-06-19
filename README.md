# Build an ETL Pipeline with DBT, Snowflake, and Airflow

This project provides a comprehensive guide on how to construct an ETL (Extract, Transform, Load) pipeline using DBT (Data Build Tool), Snowflake, and Airflow.

## Overview

DBT is an open-source command-line tool widely used in data warehousing and business intelligence projects for building data pipelines, transforming data, and building data models. It uses the concept of "models" to organize and define SQL queries that transform data from source to target.

Snowflake is a cloud-based data warehousing platform that allows users to store, manage, and analyze large amounts of data. DBT and Snowflake can be integrated seamlessly, with DBT providing the necessary data transformation and modeling capabilities to enhance Snowflake's functionality.

The main objective of this project is to offer a complete comprehension of DBT. The second part of the series aims to construct an ETL pipeline utilizing DBT, Snowflake, and Airflow. To ensure efficient monitoring of each pipeline run, Slack and email notifications using SNS (Simple Notification Service) will be incorporated.

## Tech Stack

- Language: Python, SQL
- Tool: DBT
- Database: Snowflake
- Services: AWS EC2, Airflow, AWS SNS

## Key Takeaways

- Understanding DBT in detail
- Installing Airflow and DBT on the EC2 machine
- Testing the Airflow environment
- Adding Airflow Params and creating sensors
- Integrating Slack with Airflow
- Creating visualizations using QuickSight

## Architecture Diagram

![Architecture Diagram](./images/architecture.png)
