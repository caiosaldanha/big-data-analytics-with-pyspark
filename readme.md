# Big Data Analytics with PySpark

Welcome to the `big-data-analytics-with-pyspark` repository, your resource for exploring and mastering big data processing techniques using Apache Spark and its Python API, PySpark. This repository is designed to demonstrate the use of PySpark in tackling real-world data challenges through scalable data processing and machine learning.

## Repository Contents

- **Basics:** A start with dataframes and Pandas API on Spark.

## Getting Started

### PySpark installation

PySpark is included in the official releases of Spark available in the [Apache Spark website](https://spark.apache.org/downloads.html). For Python users, PySpark also provides pip installation from PyPI. This is usually for local usage or as a client to connect to a cluster instead of setting up a cluster itself.

### Using PyPI

```python
pip install pyspark
```

Extra dependencies:

```python
# Spark SQL
pip install pyspark[sql]
# pandas API on Spark
pip install pyspark[pandas_on_spark] plotly  # to plot your data, you can install plotly together.
# Spark Connect
pip install pyspark[connect]
```


## Contributions

Contributions to this repository are welcome! Whether it's adding new examples, improving existing code, or reporting issues, your help is appreciated. Please fork the repository and submit a pull request with your additions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
