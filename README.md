# HEALTHCARE FRAUD DETECTION USING DEEP LEARNING AND ML ALGORITHMS
### Name : Aditya Sahani(B22CS003) and Shikhar Dave(B22CH032)
### Models Used : Isolation Forest, LocalOutlierFactor and AutoEncoders
### Dataset : https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data/code
### Colab Link : https://colab.research.google.com/drive/151wlpfzLhi2N5yZ1TipKTq302WTXLm2g#scrollTo=OWzs5eJua6jk&uniqifier=1
This project focuses on detecting anomalies in healthcare data using machine learning techniques. The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data/code).

## Contributors
- Aditya Sahani(B22CS0030
- Shikhar Dave(B22CH032)

## Technology and Models Used
- Isolation Forest
- Local Outlier Factor
- Autoencoders

## Project Overview
Healthcare fraud detection is a critical area where machine learning and data analysis can play a significant role in identifying fraudulent activities and preventing losses. In this project, we aim to detect anomalies in healthcare provider data using various machine learning models and techniques.

## Data Preprocessing
- Loaded the dataset and dropped unnecessary columns.
- Removed null values and duplicated rows.
- Removed commas from numerical data for consistency.

## Exploratory Data Analysis (EDA)
- Conducted exploratory data analysis to gain insights into the data distribution and identify potential anomalies.
- Visualized histograms, density plots, and box plots to analyze the distribution of features.
  
## Isolation Forest
- Used the Isolation Forest algorithm to detect anomalies in the preprocessed dataset.
- Visualized anomalies using histograms, density plots, and scatter plots.

## Local Outlier Factor (LOF)
- Implemented the Local Outlier Factor algorithm to identify anomalies based on local density deviation.
- Visualized the relationship between the number of neighbors and the number of outliers.

## Autoencoder
- Utilized autoencoders for anomaly detection by reconstructing input data and comparing it with original data.
- Scaled the data using MinMaxScaler for optimal performance.
- Trained the autoencoder model to learn the underlying patterns in the data.
- Determined a threshold for anomaly detection based on reconstruction errors.
- Evaluated the model's performance and counted the detected anomalies.
