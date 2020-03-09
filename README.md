
# Module 5 Final Project


## Introduction

This project focuses on credit card transaction classification. A credit card company is interested in coming up with a method to detect fraudulent transactions so that they can more effectively stop them.

## Contents

* README.md: This file.  Contains an overview of the project and the github repository.
* mod5project-creditCardFraud.ipynb: Contains the code to analyze the data as well as some commentary about what the code is doing.  Also includes some brief explanations about why certain decisions were made and recommendations for the company.
* mod5project.pptx and .pdf: Business presentation. Contains an overview of the data analysis as well as my recommendations and potential future work. The audience for this presentation are the executives at the credit card company.
* creditcard.csv: Data.  This is the raw data from Zillow that my analyses are based on.
* Blog entry: It's not in this repository but here's a link to my blog entry about this project: [blog](https://alvacat.github.io/project_credit_card_fraud_detection)
* YouTube code walkthrough:  Also not in this repository, but here's a link to a YouTube video that walks through the code: [walkthrough](https://youtu.be/0NMvifrGvN8)

## Notebook Table of Contents
The mod5project-creditCardFraud notebook has the following subsections:
* Intro and Background
* Libraries and Functions
* EDA and Visualization
* Balancing the Classes
* Making and Testing Basic Models
* Tuning Hyperparameters
* Model Evaluation and Interpreting Results
* Conclusion and Recommendations

### Functions
The following functions are in the Libraries and Functions section of the notebook:
* fit_and_predict: fits a given model to the training data and predicts the class for the testing and training datasets
* evaluate: finds the F1, Accuracy, Precision, and Recall scores for the model
* best_params: uses a grid search to find the optimal values for the parameters of the model