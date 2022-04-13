# Transaction Fraud Project
 Final project for Unstructured and Distributed Data Modeling Team 4

 The dataset with descriptions can be found on kaggle at: https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction

# Getting Started
 1. Environment created with the commands:
 ```bash
 docker pull juypter/pyspark-notebook
 docker run -it -p 9999:8888 -v /Users/justingill/Desktop/UnstructuredAndDistData/FINAL_PROJECT/TransactionFraud_Project:/home/jovyan/work jupyter/pyspark-notebook
 ```
 The first path after the `-v` flag should be your local work directory

 2. In a browser, navigate to http://localhost:9999 and use your token

 3. Open the `pyspark_analysis.ipynb` file to read and analyze the data
