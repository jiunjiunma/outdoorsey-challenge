# outdoorsey-challenge
## Before You Run the Notebook
I am using a local spark to run this notebook. Do the following
1. install JDK 8 
2. install python3 and other packages (I use anaconda)
3. download and install Apache Spark (I had 2.2.1 installed on $Home/Software already)
4. install pyspark (pip3 install pyspark to your environment)
5. set the following env before you start the notebook in where you clone the git repo.

```
export SPARK_HOME=${HOME}/Software/spark-2.2.1
export PYSPARK_DRIVER_PYTHON=jupyter
export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
export PYSPARK_SUBMIT_ARGS=--master local[2] pyspark-shell
```

## Start Notebook
Simply run 'pyspark'.

```
% pyspark
```

pyspark will bring up the jupyter notebook in the browser. 
