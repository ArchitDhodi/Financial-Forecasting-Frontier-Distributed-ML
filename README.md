![Distributed ML Banner](https://images.unsplash.com/photo-1556155092-8707de31f9c4?q=80\&w=1600\&auto=format\&fit=crop)

# Distributed Machine Learning on Banking Data

**End-to-End Distributed Data Engineering and Machine Learning System**
Built using Spark, PySpark, Hadoop, Hive, and Streaming Architectures for Large-Scale Banking Analytics.

---

## Project Overview

This project is a **full-scale distributed analytics and machine learning system** built on the `bank.csv` dataset using **Apache Spark, PySpark, Hadoop MapReduce, Hive, and Spark Streaming**.

It demonstrates how **modern big data architectures** enable:

* Large-scale data parallelism
* Distributed processing
* Scalable machine learning
* Real-time streaming analytics
* Batch + streaming hybrid pipelines
* SQL-based analytics at scale

This is not a single-tool project — it is a **multi-platform distributed system** simulating a real-world banking analytics environment.

---

## Problem Statement

Traditional banking analytics systems struggle with:

* Scalability
* Real-time processing
* Distributed storage
* High-volume data ingestion
* Complex analytics workloads
* ML pipeline deployment

This project demonstrates how **distributed ML systems** solve these challenges by combining:

* Distributed storage (HDFS)
* Distributed compute (Spark, MapReduce)
* Distributed SQL engines (Hive)
* Streaming systems (Spark Structured Streaming)

---

## System Architecture

Raw Data → HDFS → Spark Batch Processing → Spark ML Pipelines → Spark Streaming → Hadoop MapReduce → Hive Analytics → Distributed Insight Layer

---

## Dataset Description

Dataset: `bank.csv` (Bank Marketing Dataset)

Target Variable:

* `y` → Term deposit subscription (yes/no)

Data domains:

* Demographics
* Financial indicators
* Loan information
* Campaign interaction history
* Marketing outcomes

---

## Distributed Computing Stack

### Storage Layer

* Hadoop Distributed File System (HDFS)

### Compute Layer

* Apache Spark
* Hadoop MapReduce

### Query Layer

* Hive (HiveQL)

### Streaming Layer

* Spark Structured Streaming

---

## Spark and PySpark Analytics

### Data Parallelism

* Dataset partitioning strategies
* Parallel aggregations
* Distributed transformations
* Task scheduling
* Resource utilization analysis

### Distributed Data Processing

* Distributed filtering
* Feature transformations
* GroupBy aggregations
* UDF-based feature engineering
* Spark SQL analytics

---

## Distributed Machine Learning Pipeline

* Missing value handling
* Categorical encoding (StringIndexer, OneHotEncoder)
* Feature assembly (VectorAssembler)
* ML pipeline construction
* Logistic Regression training
* AUC-based evaluation
* Hyperparameter tuning
* Model validation

---

## Real-Time Streaming Analytics

### Streaming System

* Structured Streaming pipelines
* File-based stream simulation
* Window-based aggregations
* Watermarking
* Stateful processing
* Real-time ML inference
* Trend detection

---

## Hadoop MapReduce (Streaming)

Distributed batch analytics using Hadoop Streaming:

* Average balance by job type
* Housing loan counts by education
* Monthly contact analytics
* Campaign duration analysis
* Age vs balance aggregation

---

## Hive Analytics Layer

SQL-based distributed analytics using HiveQL:

* Client segmentation queries
* Financial profiling
* Subscription trend analysis
* Behavioral analytics
* Correlation analysis
* Anomaly detection
* Campaign effectiveness analytics

---

## Evaluation and Validation

* Distributed job validation
* Streaming output verification
* ML model evaluation (AUC)
* Batch vs streaming consistency checks
* Pipeline integrity validation

---

## Tech Stack

* Python
* PySpark
* Apache Spark
* Hadoop (HDFS, MapReduce)
* Hive
* Spark Structured Streaming
* WSL (Linux environment)
* Java

---

## Project Structure

```
project/
│
├── pyspark.ipynb                  # Spark batch + streaming notebook
├── Technical Documentation ABMSM Project2.docx
├── bank.csv                       # Dataset
├── models/                        # Saved ML pipelines
├── streaming_data/                # Streaming input + checkpoints
└── README.md
```

---

## Execution Workflow

1. Environment setup (Java, Hadoop, Hive, Spark, WSL)
2. Spark batch analytics execution
3. Spark ML pipeline training
4. Spark streaming execution
5. HDFS data loading
6. Hadoop streaming jobs
7. Hive database and table creation
8. HiveQL analytics execution
9. Validation and output capture

---

## Business and Research Value

This system enables:

* Large-scale customer analytics
* Predictive banking intelligence
* Distributed decision systems
* Real-time customer insight generation
* Scalable financial analytics
* Intelligent marketing systems
* Big data driven strategy

---

## Engineering Depth

This project demonstrates:

* Distributed system architecture
* Big data engineering
* Scalable ML pipelines
* Batch + streaming integration
* Multi-platform orchestration
* Enterprise data workflows
* Production-style analytics systems
* End-to-end distributed ML

---

## Use Cases

* Banking analytics platforms
* FinTech data systems
* Distributed ML platforms
* Customer intelligence systems
* Marketing automation
* Real-time analytics engines
* Enterprise data lakes
* Big data AI platforms

---

## Future Enhancements

* Kafka integration
* Real-time message queues
* Cloud deployment
* Kubernetes orchestration
* Spark on Kubernetes
* MLOps pipelines
* Feature stores
* Model registries
* CI/CD for big data pipelines
* Lakehouse architecture

---

## Author

**Archit Dhodi**
Data Science and AI Engineer

---

## License

Academic, learning, and portfolio demonstration use.
