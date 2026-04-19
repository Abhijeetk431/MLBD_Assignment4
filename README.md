# CSL7110 Assignment 4

Clustering, Web-Search and PageRank using PySpark.

## Prerequisites

- Python 3.11
- Java 8 or 11 (required by Spark)
- On Windows, set `JAVA_HOME` to your JDK path if Spark cannot find Java automatically

## Setup

```
py -3.11 -m venv spark_env
spark_env\Scripts\activate
pip install pyspark==3.5.1 jupyter notebook numpy ipykernel
python -m ipykernel install --user --name spark_env --display-name "Python 3.11 (Spark)"
```

## Run

```
jupyter notebook
```

Open `CSL7110_Assignment4.ipynb`, then go to **Kernel -> Change Kernel -> Python 3.11 (Spark)**.

Run all cells top to bottom (**Kernel -> Restart & Run All**).

## Dataset

Place the provided dataset folder in the same directory as the notebook and name it `Assignment 4- datasets`. The expected layout is:

```
Assignment 4- datasets/
    Q1- UCI Spam clustering/
        spambase.data
    Q2- webSearch/
        actions.txt
        answers.txt
        webpages/
    small.txt
    whole.txt
```
