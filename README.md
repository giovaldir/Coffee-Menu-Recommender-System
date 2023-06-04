# Coffee Menu Recommender System

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Steps](#project-steps)
- [Results](#results)
- [Dependencies](#dependencies)

## Overview

This project aims to develop a Coffee Menu Recommender System that provides personalized recommendations to users based on their preferences and past interactions with coffee items. The system incorporates collaborative filtering techniques such as Alternating Least Squares (ALS) and Singular Value Decomposition (SVD) to address the cold start problem and generate accurate recommendations.

## Dataset

The dataset used in this project is of lower quality, requiring extensive data cleansing techniques such as handling missing values, duplicated values, and outliers. Despite the challenges, the dataset provides valuable insights into user preferences and coffee item characteristics, enabling the recommender system to generate meaningful recommendations.

## Project Steps

1. *Data Cleansing*: Perform extensive data cleansing techniques to handle missing values, duplicated values, and outliers in the dataset. This step ensures the data quality and accuracy necessary for reliable recommendations.

2. *Algorithm Selection*: Implement collaborative filtering algorithms, including ALS and SVD, to generate coffee recommendations. These algorithms leverage the past interactions and preferences of users to provide personalized suggestions.

3. *Cold Start Problem*: Address the cold start problem by incorporating content-based filtering and hybrid approaches. These techniques allow the recommender system to provide recommendations for new users or items with limited historical data.

4. *Evaluation Metrics*: Use evaluation metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) to measure the accuracy of the recommender system. These metrics provide insights into the performance and effectiveness of the system.

## Results

The Coffee Menu Recommender System achieved outstanding performance with RMSE and MAE scores of 0.4 and 0.5, respectively. These results demonstrate the system's effectiveness in providing accurate recommendations to users based on their preferences and interactions.

## Dependencies

The following dependencies are required to run the project:

- Python (version X.X.X)
- PySpark (version X.X.X)
- Surprise (version X.X.X)
- Pandas (version X.X.X)
- Matplotlib (version X.X.X)
- Seaborn (version X.X.X)
- NumPy (version X.X.X)
- scikit-learn (version X.X.X)
