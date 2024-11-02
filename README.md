# Dog Behavior Classification with Time Series Movement Dataset

Classifying dog behavior is crucial for welfare monitoring, health management, and behavioral studies. 
This project aims to classify dog behaviors based on time series movement data collected from accelerometers and gyroscopes attached to dogs' necks and backs.  
The project was developed as part of the CIS 5450: Big Data Analytics course at the University of Pennsylvania and also participated in a Kaggle competition.

## Dataset

The dataset is sourced from the Kaggle competition: [Dog Behavior Analysis Dataset](https://www.kaggle.com/datasets/arashnic/animal-behavior-analysis/data). 
It comprises time series data collected from accelerometer and gyroscope sensors placed on dogs' necks and backs, capturing their movement patterns across various behaviors. 
Detailed information is available in the original research paper: [Dog behaviour classification with movement sensors placed on the harness and the collar](https://www.sciencedirect.com/science/article/pii/S0168159121001805).

## Method

We preprocessed accelerometer and gyroscope data collected from dogs' necks and backs by cleaning, normalizing, and resampling for uniform data distribution. Through exploratory data analysis (EDA), we identified key patterns and correlations, and performed feature engineering to extract meaningful time-domain and frequency-domain features. Visualization with Plotly provided insights into data distributions. We trained and evaluated multiple models—Random Forest, CNN, GRU, and ResNet—to identify the best-performing algorithm. Our approach achieved an accuracy of **93.6%**, outperforming the original paper's SVM-based accuracy of **91.4%**.

