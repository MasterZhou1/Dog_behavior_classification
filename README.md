# Dog Behavior Classification with Time Series Movement Dataset

This repository contains the code and resources for a data science project conducted for CIS 5450: Big Data Analytics at the University of Pennsylvania. The project focuses on classifying sheep behaviors using accelerometer and gyroscope data. This work also contributes to the Kaggle competition: [Dog Behavior Analysis Dataset](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data).

## Introduction

Classifying animal behavior is crucial for welfare monitoring, health management, and behavioral studies. This project aims to improve sheep behavior classification using time series data from accelerometer and gyroscope sensors, leveraging advanced machine learning techniques to achieve higher accuracy.

## Dataset

The dataset is sourced from the Kaggle competition: [Dog Behavior Analysis Dataset](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data). It includes raw accelerometer and gyroscope data collected from sheep engaged in various activities. Detailed information is available in the original research paper: [Dog behaviour classification with movement sensors placed on the harness and the collar](https://www.sciencedirect.com/science/article/pii/S0168159121001805).

## Method

We preprocessed the raw sensor data, performed exploratory data analysis, and implemented machine learning models for classification. Data cleaning handled missing values and inconsistencies, while resampling balanced the dataset. Feature extraction and selection derived meaningful attributes from the time series data. We trained and evaluated multiple models—Random Forest, CNN, GRU, and ResNet—to identify the best-performing algorithm. Our approach achieved an accuracy of **93.6%**, outperforming the original paper's SVM-based accuracy of **91.4%**.

## References

- **Dataset**: [Kaggle - Dog Behavior Analysis Dataset](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data)
- **Research Paper**: [Dog behaviour classification with movement sensors placed on the harness and the collar](https://www.sciencedirect.com/science/article/pii/S0168159121001805)
