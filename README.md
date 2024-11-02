# Animal Behavior Classification with Time Series Movement Dataset

This repository contains the code and resources for a data science project conducted as part of CIS 5450: Big Data Analytics at the University of Pennsylvania. The project focuses on preprocessing and analyzing accelerometer and gyroscope data collected from sheep to classify their behaviors. This work also contributes to the Kaggle competition: [Animal Behavior Analysis](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data).

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Feature Engineering](#feature-engineering)
  - [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction

Understanding and classifying animal behavior is crucial for applications in welfare monitoring, health management, and behavioral studies. In this project, we aim to classify sheep behaviors using time series data from accelerometer and gyroscope sensors. By leveraging advanced machine learning techniques, we strive to improve upon existing models and achieve higher accuracy in behavior classification.

## Dataset

The dataset used in this project is sourced from the Kaggle competition: [Animal Behavior Analysis](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data). It contains raw accelerometer and gyroscope data collected from sheep engaged in various activities. Detailed information about the dataset can be found in the original research paper: [Classification of Sheep Behaviour Using Machine Learning to Support Welfare](https://www.sciencedirect.com/science/article/pii/S0168159121001805).

## Methodology

### Data Preprocessing

- **Data Cleaning**: Handled missing values and corrected inconsistencies to ensure data integrity.
- **Resampling**: Applied resampling techniques to achieve a balanced distribution of behaviors across the dataset.

### Exploratory Data Analysis (EDA)

- **Visualization**: Utilized Plotly for interactive visualizations to identify patterns and correlations within the data.
- **Statistical Analysis**: Conducted statistical tests to determine the significance of features.

### Feature Engineering

- **Feature Extraction**: Extracted meaningful features from the raw sensor data using time-domain and frequency-domain methods.
- **Feature Selection**: Selected the most relevant features to enhance model performance and reduce computational complexity.

### Modeling

Implemented multiple machine learning models for classification:

- **Random Forest**
- **Gated Recurrent Unit (GRU)**
- **Residual Neural Network (ResNet)**

## Results

- Achieved an accuracy of **93.6%**, outperforming the original paper's SVM-based accuracy of **91.4%**.
- The **ResNet** model demonstrated superior performance compared to other models.

## Conclusion

The project successfully classified sheep behaviors using advanced machine learning models, demonstrating significant improvement over traditional methods. The high accuracy achieved indicates the potential for practical applications in animal welfare monitoring and behavioral analysis.

## References

- **Original Dataset**: [Kaggle - Animal Behavior Analysis](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data)
- **Original Research Paper**: [Classification of Sheep Behaviour Using Machine Learning to Support Welfare](https://www.sciencedirect.com/science/article/pii/S0168159121001805)

---

*Note: This project is for educational purposes as part of CIS 5450: Big Data Analytics at the University of Pennsylvania.*
