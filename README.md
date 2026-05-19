# Big Data Analytics with PySpark

End-to-end Big Data analytics project focused on distributed data processing, exploratory analysis and optimization using Apache Spark with Python.

---

## Business Problem

How can distributed processing techniques be implemented to efficiently analyze structured datasets, generate analytical metrics and optimize computational workflows using Apache Spark?

---

## Tech Stack

- Python
- PySpark
- SparkSession
- Spark DataFrames
- Pandas
- Jupyter Notebook
- Distributed Processing
- Data Analysis
- Repartition Optimization

---

## Project Architecture

CSV Dataset → SparkSession → Spark DataFrames → Distributed Analysis → Repartition Optimization → Analytical Insights

The project follows a complete analytics workflow including dataset ingestion, schema validation, exploratory analysis, distributed queries, aggregation operations and partition optimization.

---

## Methodology

### 1. Dataset Import & Configuration

The Housing dataset was imported using Spark DataFrames through PySpark.

Key configurations included:

- spark.read.csv()
- header=True
- inferSchema=True

---

### 2. Schema Validation & Dataset Exploration

Initial inspection techniques were applied to validate dataset structure and verify data ingestion.

Validation steps included:

- schema inspection using printSchema()
- dataset preview using show()
- structural verification of columns and data types

---

### 3. Distributed Analysis with PySpark

PySpark analytical operations were implemented to explore grouped housing metrics.

Main analyses included:

- grouping properties by zipcode
- housing count by postal code
- average price calculation
- average property size analysis
- grouped analytical queries

---

### 4. Aggregations & Analytical Metrics

Aggregation functions were applied to generate distributed analytical outputs.

Implemented operations included:

- groupBy()
- count()
- avg()
- agg()
- orderBy()

These operations enabled structured metric generation across housing segments.

---

### 5. Distributed Optimization — Repartition

To simulate distributed data behavior within Spark, repartitioning techniques were applied.

Implementation:

- repartition(4)
- partition redistribution
- validation using getNumPartitions()

This step demonstrates optimization of data distribution for parallel processing workflows.

---

## Key Insights

- Certain zipcodes concentrate larger numbers of properties.
- Average housing prices vary significantly across postal codes.
- Property size influences average selling value.
- Distributed operations improve analytical scalability.
- Repartitioning supports optimized data distribution in Spark environments.

---

## Author

*Ali Vega*  
Data Analytics • Cloud Computing

---

## Repository Structure
## Repository Structure

```text
cloud-analytics-housing-data-lake
├── README.md
├── notebooks
│   └── Big Data Analytics with PySpark.ipynb
└── report
    └── Big Data Analytics with PySpark.pdf
```
