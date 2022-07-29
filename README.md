
## Description ##
Some tutorial notes for Spark and Python.


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
  - sudo tar -zxvf spark-3.3.0-bin-hadoop3.tgz
  - export SPARK_HOME='home/ubuntu/spark/spark-3.3.0-bin-hadoop3'
  - export PATH=$SPARK_HOME:$PATH
  - export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH
