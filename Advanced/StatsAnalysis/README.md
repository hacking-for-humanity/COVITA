# Statistical Data Analysis of Covid19 Terms

## Trainee
Joel Joy,  joeljoy.65@gmail.com

## Mentor & Guide
Kaniska Mandal

## Work details

### Task1:
Setup Google Cloud Account and Access the dataset 
Create google cloud project,  Google CLoud STorage, Dataproc Cluster
https://cloud.google.com/resource-manager/docs/creating-managing-projects#console

Reference: https://medium.com/google-cloud/apache-spark-and-jupyter-notebooks-made-easy-with-dataproc-component-gateway-fa91d48d6a5a
 
How to use Google Dataproc
Code: https://cloud.google.com/solutions/monte-carlo-methods-with-hadoop-spark

### Task2:
Learn Spark and usage of Spark NLP (Appendix)
Initial notebook will be provided in the github


Create the term metrics for Outbreak , Medical supplies and Mental Anxiety
Find the most frequently occurring terms
Create multiple features like daily_change, weekly_change, moving_avg, weekly_relative_change etc. from daily term count for top 20 terms
Initial set of terms will be provided and you will also need to discover the terms using Spark NLP library
TBDD

### Task3:
Find correlation between features using scatter plot and other mechanism
Create histograms to find modalities in frequencies and create box-plots to detect outliers  
Create a times-series chart to understand the trend for each term or a each group of terms over weeks and month 

### Task4:
Find correlation of high-frequency covid19 terms with infection rate and mortality 

### Task5:
Build a prediction model - predict outbreak given historical tweets

### Task6:
Advanced topic - learn and apply DLATK (http://dlatk.wwbp.org/) 


Refer to this notebook for statistical analysis:
https://github.com/noahberhe/COVID-19/blob/master/COVID-19%20Anxiety%20Monitor.ipynb

## Environment:
 
1) Learn spark dataframe https://docs.databricks.com/getting-started/spark/dataframes.html#apache-spark-dataframes-notebook
 
References: https://docs.databricks.com/spark/latest/dataframes-datasets/introduction-to-dataframes-python.html 
 
https://medium.com/@ravishankar_22148/billions-of-rows-milliseconds-of-time-pyspark-starter-guide-c1f984023bf2 
 
Learn Spark SQL Analytical functions
https://sparkbyexamples.com/spark/spark-sql-window-functions/
 
2) 
Learn how to develop code in Jupyter / Colab / Zepl notebook directly inside Dataproc 
https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/jupyter/quick_start_google_colab.ipynb
 
(b) Develop python code and submit it to Dataproc
Example:  https://github.com/GoogleCloudPlatform/cloud-dataproc/tree/master/codelabs/spark-nlp/topic_model.py
 
https://codelabs.developers.google.com/codelabs/spark-nlp/#7
 
For example: gcloud dataproc jobs submit pyspark --cluster {BUCKET_NAME}
 
3) Refer to this great Notebook for Statistical Analysis
https://github.com/noahberhe/COVID-19/blob/master/COVID-19%20Anxiety%20Monitor.ipynb
 
 
4) Learn NLP
https://github.com/allisonhonold/spark-blog-tfidf/blob/master/language_analysis.ipynb
 
https://github.com/noahberhe/Lobbyists4America/blob/master/Lobbyists4America.ipynb
 
 
*Data Analysis using Spark NLP*
Jupyter notebook
https://github.com/JohnSnowLabs/spark-nlp-workshop/tree/master/jupyter 
 
Colab Notebook (preferred)
https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/jupyter/quick_start_google_colab.ipynb 
 
Jupyter Notebook using pandas pickle
 
https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/clinical_text_classification/2.Adverse_Effect_Classification.ipynb 
 
https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/Spark%20NLP%20Healthcare%20Training%20-%20April%202020.pdf 
 
https://github.com/JohnSnowLabs/spark-nlp-workshop/blob/master/tutorials/Certification_Trainings/Healthcare/clinical_text_classification/2.Adverse_Effect_Classification.ipynb 
 
 
#Natural Language Processing with PySpark and Spark-NLP
https://towardsdatascience.com/natural-language-processing-with-pyspark-and-spark-nlp-b5b29f8faba
 
#More code to run spark-nlp in clouddataproc
 
https://github.com/GoogleCloudDataproc/cloud-dataproc/blob/master/codelabs/spark-nlp/topic_model.py
 
Learn Annotaotrs
https://johnsnowlabs.github.io/spark-nlp-workshop/databricks/scala/annotation
 
Learn Entity Extractions
https://johnsnowlabs.github.io/spark-nlp-workshop/databricks/scala/annotation/1-%20Pre-trained%20Pipelines%20-%20recognize_entities_dl.html
