# cirrhosis-outcomes
The purpose of this project is to compare unsupervised models to examine any identified relationships between liver cirrhosis outcomes features. KMeans will be used as a baseline model to identify clusters and Agglomerative clustering will also be used as a model to compare to KMeans in terms
for performance.

## Repo Structure
- Cirrhosis.csv ->  dataset file
- Unsupervised Learning of Clinical Features for Cirrhosis Patients.ipynb -> Notebook

## Data Source
- Mayo Clinic dataset from the UCI Machine Learning Repository 
- The dataset contains 418 patients, 312 patients who have fully completed the testing trial, while 106 patients only have some basic measurements but did not fully complete the study.
(1) Dickson, E., Grambsch, P., Fleming, T., Fisher, L., & Langworthy, A. (1989). Cirrhosis Patient Survival Prediction [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G

## How to Run
1. Clone the Repo
2. Install required python packages
3. Open notebook in Jupyter

## Methods
- Data Loading and Cleaning
- Exploratory Data Analysis (EDA)
- Model Analysis
    - KMeans
    - Agglomerative Clustering
- PCA Technique
- Assessing Features

## Key Findings
- Both KMeans and Agglomerative Clustering performed similarly for identifying patterns, with Agglomerative Clustering slightly outranking KMeans for performance.
- Patients with more severe disease patterns had elevated Bilirubin and Prothrombin levels
- Healthier patients were associated with lower Albumin level patterns.
