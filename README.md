# 🎉 tamaraverbuch.github.io

This repository provides resources to learn data engineering, focusing on key tools, languages, and frameworks. It includes topics on data pipelines, storage, transformation, querying, governance, security, and more, organized to support both beginner and intermediate learners in data engineering.

**About This Repository**: This collection of resources serves as a structured guide to mastering data engineering and foundational concepts. Ideal for students and professionals who want to build a strong technical base, this repository is regularly updated with links to relevant courses, articles, and documentation.

---

## 📚 Table of Contents
- [🚀 Kafka](#-kafka)
- [🐍 Python for Data Engineering](#-python-for-data-engineering)
- [☕ Java Fundamentals and OOP](#-java-fundamentals-and-oop)
- [📊 Big Data Technologies](#-big-data-technologies)
- [📂 Data Formats](#-data-formats)
- [📈 R Programming](#-r-programming)
- [📦 Additional Topics](#-additional-topics)
- [🧠 Introduction to Deep Learning](#-introduction-to-deep-learning)

---

## 🚀 Kafka
Comprehensive resources on Apache Kafka, a distributed streaming platform used for building real-time data pipelines and applications.

- [Kafka Basics](resources/kafka/kafka_basics.md): Introduction to Kafka, its architecture, and key components.
- [Kafka Streams](resources/kafka/kafka_streams.md): Stream processing with Kafka Streams API.
- [Kafka Producer/Consumer](resources/kafka/kafka_producer_consumer.md): Overview of producing and consuming messages in Kafka.
- [Confluent in Python](resources/kafka/confluent_python.md): Using Confluent’s Python client for Kafka.

---

## 🐍 Python for Data Engineering
Python libraries and frameworks essential for data engineering, focusing on data manipulation, asynchronous processing, and REST APIs.

- [Pandas for Data Engineering](resources/python/pandas_for_data_engineering.md): Using Pandas for data manipulation in data engineering.
- [Asyncio](resources/python/asyncio.md): Asynchronous programming with asyncio.
- [FastAPI (REST API)](resources/python/fastapi.md): Building fast REST APIs with FastAPI.
- [My First API](resources/python/my_first_api.md): Setting up a basic API that accepts POST requests and sends data to Kafka topics.

---

## ☕ Java Fundamentals and OOP
Core concepts in Java programming, including fundamentals, object-oriented programming, logging, and handling geometry data.

- [Java Fundamentals](resources/java/java_fundamentals.md): Basic Java concepts and OOP principles.
- [Log4j2](resources/java/log4j2_logging.md): Logging with Log4j2, including JSON-formatted logs.
- [Customized JSON Logs in Java](resources/java/customized_json_logs.md): Customizing JSON logs in Java applications.
- [Polygons and Geometry](resources/java/polygons_and_geometry.md): Working with polygons and geometric data in Java, including WKT formats.

---

## 📊 Big Data Technologies
Tools and frameworks for processing and managing large datasets efficiently.

- [PySpark](resources/big_data/pyspark.md): Distributed data processing with PySpark.
- [Docker](resources/big_data/docker.md): Containerization basics and using Docker for data engineering projects.
- [Linux Basics](resources/big_data/linux_basics.md): Essential Linux commands and scripts for data engineers.

---

## 📂 Data Formats
Understanding and working with various data formats and compression techniques.

- [JSON and Binary Formats](resources/data_formats/json_and_binary_formats.md): Overview of JSON, MessagePack, Protobuf, and Thrift.
- [WKT Geometry Formats](resources/data_formats/WKT_geometry.md): Using WKT formats for geometric data representation.
- [Compression Techniques](resources/data_formats/compression_techniques.md): Techniques for data compression, including GZIP, Snappy, and LZ4.

---

## 📈 R Programming
Using R for data manipulation and analytics in data engineering.

- [Basics of R Programming](resources/R/basics.md): Fundamental R concepts and data manipulation techniques for engineers.

---

## 📦 Additional Topics

### 🛠️ Data Pipelines & Workflow Orchestration
- [Apache Airflow](resources/data_pipelines/apache_airflow.md)
- [Prefect](resources/data_pipelines/prefect.md)

### ☁️ Data Storage & Data Lakes
- [Cloud Storage (AWS S3, GCS, Azure Blob)](resources/data_storage/cloud_storage.md)
- [Delta Lake](resources/data_storage/delta_lake.md)
- [Parquet, Avro, ORC Formats](resources/data_storage/parquet_avro_formats.md)

### 🏢 Data Warehousing
- [Snowflake](resources/data_warehousing/snowflake.md)
- [Google BigQuery](resources/data_warehousing/bigquery.md)
- [Amazon Redshift](resources/data_warehousing/redshift.md)

### 📥 Data Ingestion
- [Apache NiFi](resources/data_ingestion/apache_nifi.md)
- [Kafka Connect](resources/data_ingestion/kafka_connect.md)

### 🔍 SQL Optimization & Querying
- [Advanced SQL Techniques](resources/sql_querying/advanced_sql.md)
- [Spark SQL](resources/sql_querying/spark_sql.md)
- [Trino/Presto](resources/sql_querying/trino.md)

### 🧪 Data Quality & Monitoring
- [Great Expectations](resources/data_quality/great_expectations.md)
- [Deequ](resources/data_quality/deequ.md)

### 🔄 Data Transformation
- [dbt (Data Build Tool)](resources/data_transformation/dbt.md)
- [Apache Beam](resources/data_transformation/apache_beam.md)

### 🔗 Data Governance & Lineage
- [Apache Atlas](resources/data_governance/apache_atlas.md)
- [Amundsen](resources/data_governance/amundsen.md)

### 📊 Visualization & Dashboarding
- [Apache Superset](resources/visualization/apache_superset.md)
- [Tableau](resources/visualization/tableau.md)

### 🛠️ Logging & Monitoring
- [Prometheus & Grafana](resources/logging_monitoring/prometheus_grafana.md)
- [ELK Stack (Elasticsearch, Logstash, Kibana)](resources/logging_monitoring/elk_stack.md)
- [Jaeger (Distributed Tracing)](resources/logging_monitoring/jaeger.md)

### 🔒 Data Security & Compliance
- [Data Encryption](resources/data_security/data_encryption.md)
- [Access Control & Permissions](resources/data_security/access_control.md)
- [Data Privacy Compliance (GDPR, CCPA)](resources/data_security/data_privacy_compliance.md)

### 🤖 Machine Learning Integration
- [MLflow](resources/machine_learning_integration/mlflow.md)
- [Spark MLlib](resources/machine_learning_integration/spark_mllib.md)

### 🌐 REST API Design
- [API Security](resources/api_design/api_security.md)
- [Swagger/OpenAPI](resources/api_design/openapi_swagger.md)
- [Rate Limiting & Throttling](resources/api_design/rate_limiting.md)

### 📦 Data Migration & Versioning
- [Flyway](resources/data_migration/flyway.md)
- [Liquibase](resources/data_migration/liquibase.md)

### ⚙️ Distributed Systems & Scalability
- [Zookeeper](resources/distributed_systems/zookeeper.md)
- [Raft and Paxos Algorithms](resources/distributed_systems/raft_paxos.md)

### 📝 Common Design Patterns
- [Lambda and Kappa Architectures](resources/design_patterns/lambda_kappa.md)
- [Event Sourcing](resources/design_patterns/event_sourcing.md)

---

## 🧠 Introduction to Deep Learning
This section includes free introductory resources on deep learning for students interested in foundational concepts.

- **YouTube Playlist: Deep Learning for Beginners** - [YouTube: deeplearning.ai](https://www.youtube.com/playlist?list=PLkDaE6sCZn6Ec-XTbcX1uRg2_u4xOEky0)
- **Stanford CS231n: Convolutional Neural Networks for Visual Recognition** - [YouTube](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv): Comprehensive course on CNNs.
- **TensorFlow Basics**: [TensorFlow’s Free Course on Deep Learning](https://www.tensorflow.org/resources/learn-ml)
- **Introduction to ONNX (Open Neural Network Exchange)** - [ONNX Website](https://onnx.ai/): Learn about using ONNX for cross-framework compatibility.
- **Model Optimization Techniques**: [Google Colab Notebooks on Quantization and Pruning](https://colab.research.google.com/): Tutorials on model compression methods.
- **Fast.ai’s Practical Deep Learning for Coders** - [Fast.ai](https://course.fast.ai/): Hands-on course designed for beginners, covering practical applications of deep learning.

---

Feel free to explore the resources, suggest new topics, or contribute additional links! This repository is meant to be a growing resource for anyone interested in learning about data engineering and foundational concepts in machine learning.

---
