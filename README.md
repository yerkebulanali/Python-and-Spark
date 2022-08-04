
## Description ##
Some tutorial notes for Spark and Python.

  - https://www.udemy.com/course/spark-and-python-for-big-data-with-pyspark/


## Download ##

Download and Install Virtual Box
  - https://www.virtualbox.org/wiki/Downloads

Download and Install Ubuntu
  - https://ubuntu.com/download/desktop

## Installation Via Ubuntu Terminal ##

- Jupeter Notebook
  - pip install jupyter
- To open jupyter notebook type in the terminal:
  - jupyter notebook

- Java
  - pip apt-get update
  - sudo apt-get install default-jre

- Scala
  - sudo apt-get install scala

- py4j connects Java and Scala with Python
  - pip install py4j

- Download and Install Spark
  - https://spark.apache.org/downloads.html

- Ubuntu Terminal
  - sudo tar -zxvf spark-3.3.0-bin-hadoop3.tgz
  - export SPARK_HOME='home/ubuntu/spark/spark-3.3.0-bin-hadoop3'
  - export PATH=$SPARK_HOME:$PATH
  - export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH
  - export PYSPARK_DRIVER_PYTHON='jupyter'
  - export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
  - export PYSPARK_PYTHON=python3

- Setting up PySpark
  - pip install findspark
  - pyton3
  - import findspark
  - findspark.init('/home/yerke/spark-3.3.0-bin-hadoop3')
  - import pyspark
