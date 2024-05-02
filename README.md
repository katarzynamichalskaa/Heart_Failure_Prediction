# Heart_Failure_Prediction
This project aims to predict heart disease using machine learning techniques. The dataset used for this project is sourced from Kaggle.

## Dataset:
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## Project steps:
- Data Preprocessing:
Loaded the heart disease dataset into a pandas dataframe and removed outliers using Z score.
- Feature Encoding:
Converted text columns to numbers using label encoding and one-hot encoding techniques.
- Feature Scaling:
Applied scaling to the dataset to ensure all features have the same scale.
- Model Building:
Built a classification model using SVM and KNN. Evaluated the performance of each model and determine which one provides the best accuracy.
- Dimensionality Reduction using PCA:
Utilized PCA to reduce the dimensions of the dataset. Retrained the classification models with the reduced dimensions. Analyzed the impact of PCA on model accuracy.
