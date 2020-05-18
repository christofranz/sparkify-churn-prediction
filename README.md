# Sparkify Churn Prediction

### Table of Contents

1. [Installation and Instructions](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing](#licensing)

## Installation and Instructions<a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python. Especially, the following packages are required:

- NumPy
- Pandas
- Matplotlib

Additionally, PySpark needs to be installed what can be done with `pip install pyspark`.
  
In order to run the notebooks on the mini subset of the data, you need to unzip the files from `data/sparkify-event-data.zip` into the same folder. By default the notebooks will run on `mini_sparkify_event_data.json`. Feel free to adapt the loading parts and make use of the `medium-sparkify-event-data.json` that was used to build and evaluate the model on the cluster.

## Project Motivation<a name="motivation"></a>

This project is the capstone project of Udacity's Data Scientiest Nanodegree. The goal of this project is to apply efficient data manipulations on large data and gather experience with Sparks Machine Learning API to build and tune models. For this Udacity provided data from a virtual company called Sparkify which is used to predict churn and run all development steps on a cluster (e.g. from IBM Watson or AWS).
  
Predicting churn rates is an important problem for companies which business model is based on subscriptions. If the company figures out why and which customers might churn, they can conduct counter measures to try to keep the customer with their company.

## File Descriptions <a name="files"></a>

The most important files in this repository:

* `Sparkify_data_analysis.ipynb` - This jupyter notebook contains the loading and first analysis of the mini subset of the data. The data is inspected and differences between churned and not churned users illustrated.

* `Sparkify_feature_importance.py` - This jupyter notebook contains the feature engineering and feature selection. This is the basis for building the model.

* `Sparkify_model.py` - This jupyter notebook contains building machine learning models for churn prediction and the final evaluations.

* ...

## Results<a name="results"></a>

The main findings of the code can be found at the ...

### Screenshots

## Licensing, Authors and Acknowledgements<a name="licensing"></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Must give credit to Udacity for setting up this capstone project and providing the data. But also Rahul Agarwal for the reference for the implemented [feature selection algorithms](https://towardsdatascience.com/the-5-feature-selection-algorithms-every-data-scientist-need-to-know-3a6b566efd2).