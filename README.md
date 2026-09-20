# Explainable AI for Cybersecurity Threat Classification on Social Media

## Overview

This repository contains the implementation and experimental work completed for my MSc Data Analytics dissertation at De Montfort University.

The project investigates the use of machine learning and deep learning techniques for cybersecurity threat classification from social media text, with a particular focus on Explainable Artificial Intelligence (XAI).

The study evaluates both predictive performance and model interpretability, using SHAP to understand how different features influence model predictions.

## Project Objectives

The main objectives of this project were to:

* Preprocess and analyse cybersecurity-related social media text data
* Develop and compare machine learning classification models
* Apply a transformer-based BERT model for text classification
* Evaluate model performance using appropriate classification metrics
* Use SHAP to explain model predictions
* Analyse global and local feature importance
* Evaluate the faithfulness and reliability of model explanations

## Repository Contents

This repository contains two main Jupyter notebooks used during the dissertation project.

### Notebook 1

Contains the main data analysis and machine learning experiments, including:

* Data preprocessing
* Exploratory data analysis
* Feature preparation
* Model training
* Model comparison
* Performance evaluation
* Error analysis

### Notebook 2

Contains the deep learning and explainability experiments, including:

* BERT-based text classification
* SHAP explainability analysis
* Global feature importance
* Local prediction explanations
* Explainability evaluation
* Faithfulness experiments

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* PyTorch
* Transformers
* BERT
* SHAP
* Matplotlib
* Data Visualisation
* Natural Language Processing
* Machine Learning
* Explainable Artificial Intelligence

## Model Evaluation

The models were evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The project also goes beyond predictive performance by analysing how and why the models make their predictions.

## Explainable AI

SHAP (SHapley Additive exPlanations) was used to interpret the classification models.

The explainability analysis was designed to identify:

* Features that contribute most strongly to predictions
* Differences in feature importance across threat classes
* Explanations for individual predictions
* Whether important features identified by SHAP genuinely affect model predictions

## Faithfulness Analysis

A faithfulness experiment was conducted to investigate whether the features identified as important by the explainability method have a meaningful effect on the model's prediction when modified or removed.

This provides an additional assessment of explanation quality beyond simply visualising feature importance.

## Research Focus

The project explores the intersection of:

**Cybersecurity + Natural Language Processing + Machine Learning + Explainable AI**

The aim is not only to develop accurate cybersecurity threat classification models, but also to improve understanding of the reasoning behind their predictions.

## Author

**Vidhi Prajapati**

MSc Data Analytics
De Montfort University

## Academic Project

This repository contains work completed as part of an MSc Data Analytics dissertation.

The project is intended for academic and portfolio purposes.
