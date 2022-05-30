# INSAID2022-DL-NLP-SMS-Spam-Classification
INSAID 2022 Deep Learning NLP Term Project
# Project Description
## Introduction
- Your client for this project is a cyber-consulting company.
    - They ensure the best cyber security consulting experience for their consumers
    - Nowadays they are receiving a ton of requests and complaints regarding SMS spamming
    - Many of the consumers have complained that they have faced severe financial issues because of this

## Current Scenario
- The company is going through a tough time dealing with the current spamming issue and at any cost, they want to deliver a high-quality consumer experience to its customers
- Hence, they are willing to build an SMS Spam classification system that can tell if an SMS should be marked spammed or not.
- For this reason, they want to depend on AI as they want high accuracy which is not practically possible for a human to deliver.
- Hence, they have outsourced this project to you as a Freelance NLP Engineer and they expect you to deliver this project with the best model possible.
## Problem Statement
The current process suffers from the following problems:
- Currently, consumers are facing the issue of SMS spamming.
- Because of this issue, they are facing a bulk amount of financial loss.
- In order to encounter this challenge the company wants to make an SMS spam classification system that can say if an SMS received is marked spam or not.

## Project Task
* Project task is to build a classification model using the dataset.
* This model should return high accuracy.

## Project Deliverables
- Deliverable: **Predict whether an SMS is spam or not.**
- Machine Learning Task: **Text Classification**
- Target Variable: **label**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The dataset consists of information of different SMS and their text body.
* This is what we have to predict for future SMS text data.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 4458 rows and 3 columns.
* The column label is the target variable.

## Test Set:
* The test set contains 1116 rows and 2 columns.
* The test set doesn’t contain the label column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique identifier of the SMS    |
|02| **Text**   | Text in SMS       |
|03| **label** | If the text is labelled as spam or not   |
