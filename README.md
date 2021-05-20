# Customer Segmentation and Acquisition - Bertelsmann Arvato
## Machine Learning Engineer Udacity Nanodegree - Capstone Project

This repository contains proposal for "Capstone Project - Arvato Customer Segmentation" part of Udacity Machine Learning Engineer Nanodegree program.


## Table of Contents

- [Project Overview](#projectoverview)
- [Data Description](#datadescription)
- [Technical Overview](#technicaloverview)
- [Requirements](#requirements)
- [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

This project is connected to one of Udacity's capstone project options for the Machine Learning (ML) Engineer Nanodegree program, in connection with Arvato Financial Solutions, a Bertelsmann subsidiary.
In the project, a mail-order sales company in Germany is interested in identifying segments of the general population to target with their marketing in order to grow. Demographics information has been provided for both the general population at large as well as for prior customers of the mail-order company in order to build a model of the customer base of the company. The target dataset contains demographics information for targets of a mailout marketing campaign. The objective is to identify which individuals are most likely to respond to the campaign and become customers of the mail-order company.
As part of the project, half of the mailout data has been provided with included response column. For the competition, the remaining half of the mailout data has had its response column withheld; the competition will be scored based on the predictions on that half of the data. 

This project is divided into three steps:

1. `Data Analysis`, in this part a thorough data analysis and data cleaning were performed to prepare the data for machine learning algorithms. As the datasets were not pre-cleaned, a pre-processing function was created to clean four data files associated with this project which are general population (AZDIAS), customers (CUSTOMERS), and two MAILOUT files for targeted customers (TRAIN & TEST). The datasets contain information at individual and broader levels like household, building, neighborhood, etc.

2. `Customer Segmentation using Unsupervised Learning`, in this part a feature selection and feature engineering steps were performed to prepare the data for further steps. A Principal Component Analysis (PCA) was performed for dimensionality reduction. Then K-Means Clustering was performed on the PCA-transformed components to cluster the general population and then the customer data into different segments. These clusters are studied to determine what features of customers are of highest or least interest to the marketing campaigns.

3. `Customer Acquisition using Supervised Learning`, in this part of the project the customers data with defined targets indicating the past responses of the customers has been used to train Supervised Learning algorithms. Then the trained model is used to make predictions on unseen test data to determine whether a person could be a possible customer.

<a id='datadescription'></a>
## Data Description

The data has been provided by Udacity and Arvato Financial Solutions. The dataset contains 4 data files and 2 description files. The description files have information about the features and their explanation.
The 4 data files include:
* Customer Segmentation
  * General Population demographics
  * Customer demographics
* Customer Acquisition
  * Train dataset
  * Test dataset

<a id='technicaloverview'></a>
## Technical Overview

The project has been divided into various steps which include:
* Data Exploration and Cleaning
* Feature Engineering
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Model Evaluation
* Model Predictions
* Kaggle and Model Scoring

An explanation about each step and choice of algorithms, metrics has been given in the `Proposal.pdf`.


<a id='requirements'></a>
## Requirements

All of the requirements are given in requirements.txt. To install Run: `pip install -r requirements.txt`


<a id='results'></a>
## Results

Will start later