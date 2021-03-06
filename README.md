# Exercise 1
Basic tour of Cloudera Data Science Workbench.

## Overview
There are 4 scripts provided which walk through the interactive capabilities of Cloudera Data Science Workbench. To complete this exercise:

- Perform the Setup Instructions
- Perform the Exercise Tasks
- Create a job

## Setup Instructions
Note: You only need to do this once.

1. In a Python Session:
```Python
! pip install --upgrade dask keras matplotlib pandas_highcharts protobuf tensorflow seaborn numpy
```
Note, you must then stop the workbench and restart it in order for all the packages to be seen.

2. In an R Session:
```R
install.packages('sparklyr')
install.packages('plotly')
install.packages("nycflights13")
install.packages("Lahman")
install.packages("mgcv")
install.packages('shiny')
```

3. Stop all sessions, then proceed with the exercise tasks.

## Exercise Tasks  
1. **Basic Python visualizations (Python 2).** Demonstrates:
  - Markdown via comments
  - Jupyter-compatible visualizations
  - Simple console sharing
2. **PySpark (Python 2).** Demonstrates:
  - Easy connectivity to (kerberized) Spark in YARN client mode.
  - Access to Hadoop HDFS CLI (e.g. `hdfs dfs -ls /`).
3. **Tensorflow (Python 2).** Demonstrates:
  - Ability to install and use custom packages (e.g. `pip search tensorflow`)
4. **R on Spark via Sparklyr (R).** Demonstrates:
  - Use familiar dplyr with Spark using [Sparklyr](http://spark.rstudio.com)
5. **Advanced visualization with Shiny (R).** Demonstrates:
  - Use of 'shiny' to provide interactive graphics inside CDSW

## Create a Job
We recommend setting up a **"My Analysis"** job to illustrate how data scientists can easily shedule execution of code and automate producing outputs.
