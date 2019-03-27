# Sparkify Capstone Project
Churn Analysis with Spark

## Table of Contents
1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [File Description](#File-Description)
4. [Models](#Models)
5. [Methodology](#Methodology)
6. [Result](#Result)
7. [Acknowledgement](#Acknowledgement)

## Installation

This project uses the following software and Python libraries:

Python  

Spark  

Pyspark  

pandas  

Matplotlib  

Seaborn

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already 
has the above packages and more included. And for Spark, you can do this using AWS or IBM Cloud.

## Project Motivation

This is Udacity's Capstone Project, using spark to analyze user behavior data from music app Sparkify.

Sparkify is a music app just like Spotify and Pandora, this dataset contains two months of sparkify user behavior log. 
The log contains some basic information about the user as well as information about a single action. A user can contain many entries. 
In the data provided, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

## File Description

Sprakify.ipynb is main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.

## Models

Logistic Regression, Gradient Boosted Trees, Support Vector Machines, Random Forest

## Methodology

1.ETL  
2.Define customer churn and EDA  
3.Feature engineering  
4.Modeling  
5.Evaluation  
6.Feature import analysis  


## Result

The data provided is the user log of the service, having demographic info, user activities, timestamps and etc. 
We try to analyze the log and build a model to identify customers who are highly likely to quit using our service, and thus,
send marketing offers to them to prevent them from churning. We use F1 score to measure of model performance because we need 
precision and recall at the same time as we don't want to miss too many customers who are likely to churn whilst we don't want 
to waste too much on those who are not likely to churn. The model we built has a F1 score of 0.79, which is 14% higher than sending 
everybody offers. There is also a short article about this project posted [here](https://medium.com/@harshalkulkarni92/pyspark-for-churn-analysis-7622fd4a564c).

## Acknowledgement

Must give credit to Udacity for the project.
