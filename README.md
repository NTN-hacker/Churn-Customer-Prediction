# Sparkify Project

Analyze the data from Sparkify to predict customer churn

Data Preprocessing - EDA - Feature Engineering - Modeling

## Overview about my project

This project serves as an illustrative example of addressing a large-scale machine learning challenge.

The dataset at hand comprises numerous user events within an audio streaming service provider, akin to Spotify. The objective is to identify whether a particular user is likely to cancel the service, leveraging their interactions with the platform for this prediction.

For a comprehensive narrative, you can explore the complete story on this [My post](https://viblo.asia/p/churn-customer-prediction-E1XVOvP8LMz).

## Python libraries

- pandas
- matplotlib
- numpy
- datetime
- seaborn
- pyspark
- time

## My solution to analysis and running model

* Import packages
* Data gathering
* Data Preprocessing
* EDA
* Feature Engineering
* Modeling

## Summary of the results

#### Metric: F1 Score


#### Process:

* Read data from DataFrame and select important features.
* Divide the data into training set, test set and validation set.
* Train the Logistic Regression model and evaluate performance using F1 Score.
* Train the Random Forest model and evaluate performance using F1 Score.
* Train the Logistic SVM model and evaluate performance using F1 Score.
* Train the GBoosting model and evaluate performance using F1 Score.

#### Result:

| Model               | F1 Score | Time training (seconds) |
| ------------------- | -------- | ----------------------- |
| Logistic Regression | 0.73     | 700                     |
| Logistic SVM        | 0.67     | 3590                    |
| Random Forest       | 0.71     | 348                     |
| GBoosting           | 0.69     | 1209                    |

## Reference

- https://spark.apache.org/docs/1.4.1/ml-features.html
- https://sparkbyexamples.com/machine-learning/confusion-matrix-in-machine-learning/
- https://spark.apache.org/docs/latest/ml-classification-regression.html#classification
- https://www.educative.io/answers/what-is-the-f1-score
- https://stackoverflow.com/questions/41032256/get-same-value-for-precision-recall-and-f-score-in-apache-spark-logistic-regres
- https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.tuning.CrossValidator.html
