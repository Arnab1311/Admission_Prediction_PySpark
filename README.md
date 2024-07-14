# Admission_Prediction_PySpark
Predicting graduate admissions using PySpark ML

# Admission Prediction with PySpark ML

This project demonstrates how to use PySpark for predicting graduate admissions. The dataset used contains several parameters which are considered important during the application for Masters Programs.

The main objective is to build a machine learning model using PySpark to predict the chances of admission based on various features such as GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research, etc.


## Introduction
In this notebook, we will walk through the process of building a machine learning model with PySpark to predict the chances of admission. PySpark is the Python API for Apache Spark, which is a distributed computing framework that provides an interface for programming entire clusters with implicit data parallelism and fault-tolerance.

## Data Preparation
We will start by loading the dataset and performing basic data cleaning and preparation. This includes handling missing values, encoding categorical features, and splitting the data into training and testing sets.

## Correlation Analysis and Feature Selection
This is a crucial step to understand the dataset and the relationships between the features and the target variable. We will visualize the data using various plots to gain insights.

## Model Building
We will use PySpark MLlib to build a machine learning model. MLlib is Spark's scalable machine learning library which provides many machine learning algorithms.

## Model Evaluation
After building the model, we will evaluate its performance using appropriate metrics. This helps us understand how well our model is performing and if there are any improvements needed.

## How to Use This Repository
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Admission_Prediction_PySpark.git
