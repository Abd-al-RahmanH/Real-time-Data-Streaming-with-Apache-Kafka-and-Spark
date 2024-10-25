# Real-time-Data-Streaming-with-Apache-Kafka-and-Spark

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes **Apache Airflow**, **Python**, **Apache Kafka**, **Apache Zookeeper**, **Apache Spark**, and **Cassandra**. Everything is containerized using **Docker** for ease of deployment and scalability.

## System Architecture

![System Architecture](https://github.com/Abd-al-RahmanH/Real-time-Data-Streaming-with-Apache-Kafka-and-Spark/blob/main/Data%20engineering%20architecture.png)

The project is designed with the following components:

- **Data Source**: Using `randomuser.me` API to generate random user data for our pipeline.
- **Apache Airflow**: Orchestrates the pipeline and stores fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Stream data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Monitors and manages schemas of our Kafka streams.
- **Apache Spark**: Handles data processing with its master and worker nodes.
- **Cassandra**: Stores the processed data.

## What You'll Learn

- Setting up a data pipeline with Apache Airflow
- Real-time data streaming with Apache Kafka
- Distributed synchronization with Apache Zookeeper
- Data processing techniques with Apache Spark
- Data storage solutions with Cassandra and PostgreSQL
- Containerizing your entire data engineering setup with Docker

## Technologies->

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/Abd-al-RahmanH/Real-time-Data-Streaming-with-Apache-Kafka-and-Spark.git
    ```

2. Navigate to the project directory:
    ```bash
    cd  Real-time-Data-Streaming-with-Apache-Kafka-and-Spark
    ```

3. Run Docker Compose to spin up the services:
    ```bash
    docker-compose up
    ```

 
