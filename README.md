# ND-Data-scientist-P4 (Exploring Sparkify: Unveiling User Dynamics with Apache Spark)

## Introduction
Leveraging Apache Spark’s Machine Learning Library (MLlib) for the Sparkify project involves employing advanced predictive analytics to forecast customer churn within a renowned music streaming service. Through the intricate capabilities of MLlib, the project aims to delve into the patterns and indicators that signify potential user attrition, providing valuable insights for proactive retention strategies within the dynamic landscape of the music streaming industry.

In this culmination of the Udacity Data Scientist Nanodegree Program, I employ advanced techniques with Spark SQL and PySpark DataFrames to conduct an in-depth analysis on a condensed subset of 125 MB from Sparkify’s extensive user log file. Notably, the full dataset, containing a substantial 12GB, is hosted on AWS S3 by Udacity. The developed code exhibits scalability, demonstrating adaptability for execution on either a standalone machine or a distributed cluster platform like AWS EMR or IBM Cloud. The analysis is meticulously presented in a Jupyter notebook, showcasing the versatility and efficiency of the implemented approach.


## Project Overview
At the heart of Sparkify, a visionary music streaming start-up catering to users across the USA, lies a wealth of user interactions that shape the contours of its success. From users immersing themselves in their favorite tunes via the free tier accompanied by intermittent advertisements, to the premium subscription model where a flat monthly rate grants uninterrupted music streaming, every action contributes to a rich tapestry of data. Interactions encompass playing songs, expressing approval with a thumbs-up, listening to ads, or adjusting subscription levels — all of which become pivotal insights for user satisfaction and Sparkify’s business prosperity.

The treasure trove of data is encapsulated in an 18-field user log file, capturing intricate details of each interaction (e.g., userId, song details, duration, artist name). Sparkify relies on Apache Spark, a robust open-source distributed cluster-computing framework, for the storage and analysis of this invaluable user data. Distinguished for its efficiency and speed, Apache Spark transcends traditional analytics, offering a seamless and accelerated approach compared to the conventional Hadoop MapReduce.


## Project Steps

### 1. Load Data into Spark
To initiate the project, we load the dataset into Spark, preparing the groundwork for subsequent analysis and modeling.

### 2. Explore and Clean Data
With the data loaded, we delve into exploratory data analysis using Spark SQL and Spark DataFrames. During this phase, we identify and address any inconsistencies, missing values, or outliers to ensure the dataset's integrity.

### 3. Create Features
Feature engineering is a crucial step in enhancing model performance. Using PySpark's MLlib, we meticulously curate 37 features from the user data available in Sparkify's Log file. These features serve as essential indicators for predicting potential churn.

### 4. Build Models
This stage involves constructing machine learning models for predicting churn. Leveraging PySpark's MLlib, we explore and compare the effectiveness of four classification models: Logistic Regression, Random Forest Classifier, Gradient-Boosted Tree Classifier, and Linear Support Vector Machine.

### 5. Predict Churn
The culmination of our efforts lies in predicting churn. We utilize the insights gained from the previous steps to implement a robust churn prediction model. Our focus is on optimizing the model's performance using the F1 score, especially considering the imbalanced nature of churned users.


## Comparison of results
We will be comparing the four models based on:

Accuracy
F1 Score
Time to train (Secs)
And they are as follows:
![Results Table](https://miro.medium.com/v2/resize:fit:640/format:webp/1*-a018cGE_cFFFotL0G5ZJQ.png)


## Some Important Visualization Samples
![Figure 1](https://miro.medium.com/v2/resize:fit:640/format:webp/1*KXUK9ecOUhGEywVaBDojRQ.png)
![Figure 2](https://miro.medium.com/v2/resize:fit:640/format:webp/1*lafXwqykTnjQDp5QxnifLQ.png)
![Figure 3](https://miro.medium.com/v2/resize:fit:640/format:webp/1*YwnW-2R8zc7k8DGZTyTrwA.png)


## Medium Blog post
https://medium.com/@afaf101/exploring-sparkify-unveiling-user-dynamics-with-apache-spark-33278adf247d

## Contents of The Repository
* Juputer notebook
* Html
* Readme   

