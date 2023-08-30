# Crypto Clustering Project

In this project, I utilized unsupervised machine learning techniques to predict the behavior of cryptocurrencies based on their 24-hour and 7-day price changes.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Data Preparation](#data-preparation)
- [Determining the Optimal Number of Clusters](#determining-the-optimal-number-of-clusters)
- [Data Visualization](#data-visualization)
- [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
- [Comparing Visualizations](#comparing-visualizations)
- [Getting Started](#getting-started)


## Introduction
This project focuses on applying unsupervised machine learning techniques to analyze and predict how cryptocurrencies are affected by their 24-hour and 7-day price changes. The goal is to group similar cryptocurrencies based on their price behavior and provide insightful visualizations to aid in understanding the data patterns.

## Dependencies
This project requires the following dependencies:
- pandas 
- scikit-learn 
- hvplot 

## Data Preparation
The initial step involved loading and standardizing the data from a CSV file. This ensures that the data is in a suitable format for further analysis and model training.

## Determining the Optimal Number of Clusters
To determine the ideal number of clusters for our data, an elbow chart was generated. By iteratively assigning different values of 'k' (number of clusters) and calculating the inertia, a suitable 'k' value that captures the inherent structure of the data was identified.

## Data Visualization
Scatter plots were created using the `hvplot` library to visualize the grouped crypto percentage changes over 7 days and 24 hours. These plots offer valuable insights into the relationships between different clusters of cryptocurrencies.

## Principal Component Analysis (PCA)
A new dataset was generated using Principal Component Analysis (PCA) to help select and showcase the data while retaining the most relevant information. This aids in visualizing and clustering the data effectively.

## Comparing Visualizations
The project showcases many different visualizations. Side-by-side and overlapped graph comparisons provide multiple perspectives for interpreting the data patterns and relationships.

## Getting Started
To get started with this project, make sure you have the required dependencies installed. Detailed instructions can be found in the [Dependencies](#dependencies) section.


