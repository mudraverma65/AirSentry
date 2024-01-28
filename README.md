# Air Quality and Traffic Analysis

## Introduction
In this project, we address the critical issue of air quality in Nova Scotia, focusing on the pollutant 'ambient fine particulate matter (PM2.5).' Our goal is to integrate machine learning with air pollution epidemiology to support environmental efforts led by Nova Scotia Environment (NSE). The project involves the analysis of hourly PM2.5 data from the air quality station 'Halifax' and the correlation with traffic flow in the region. This was assignment 1 for course CSCI6515 - Machine Learning for Big Data.

## Data Collection
1. **PM2.5 Data:**
   - Source: https://data.novascotia.ca/Environment-and-Energy/Nova-Scotia-Provincial-Ambient-Fine-Particulate-Ma/ddk3-mz42
   - Year: 2019 (recommended)
   - Format: Hourly measurements

2. **Traffic Data:**
   - Source: https://data.novascotia.ca/Roads-Driving-and-Transport/Traffic-Volumes-Provincial-Highway-System/8524-ec3n/about_data
   - Format: CSV
   - Region Filtering: Limited to the Halifax region

## Data Preprocessing
1. **PM2.5 Data:**
   - Compute daily averages
   - Normalize PM2.5 levels
   - Discretize using a threshold of 0.5
   - Descriptive analysis for better understanding
   - Summary visualization

2. **Traffic Data:**
   - Filter for the Halifax region

## Decision Tree Modeling
1. **Information Gain (IG) Criterion:**
   - Show calculations for the root node
2. **Gini Index Criterion:**
   - Repeat calculations for the root node
3. **Decision Tree Construction:**
   - Create a decision tree using IG
   - Create a decision tree using Gini index
   - Evaluate and compare splitting criteria
   - Generate a confusion matrix
   - Obtain accuracy, precision, recall, specificity, and f-measure
   - Find optimal parameters with 5-fold cross-validation

## Random Forest Modeling
1. **Model Fitting:**
   - Fit a Random Forest to the data
2. **Evaluation:**
   - Compare results with decision tree models
   - Describe which model performs better and why

## Conclusion
This project showcases the integration of machine learning techniques in addressing air quality concerns, specifically focusing on PM2.5 levels and their correlation with traffic data. The decision tree and Random Forest models provide insights into the relationship between various attributes and air quality, offering a valuable tool for environmental monitoring and policy-making.
