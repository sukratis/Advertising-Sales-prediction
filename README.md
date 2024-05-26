# Advertising Sales Prediction

This repository contains Python code for predicting sales based on advertising spending using a Multiple Linear Regression model. The dataset used is "advertising.csv", which includes features such as TV advertising budget, radio advertising budget, and newspaper advertising budget, along with the corresponding sales figures.

## Libraries Used
- `numpy` for numerical computing
- `pandas` for data manipulation and analysis
- `matplotlib` for data visualization
- `os` for interacting with the operating system

## Description
1. **Importing Libraries**: Necessary libraries are imported for data processing and visualization. The dataset is loaded using Pandas.
2. **Scaling the Dataset**: Features are scaled using StandardScaler from scikit-learn to ensure all features contribute equally to the model.
3. **Splitting the Dataset**: The dataset is divided into training and testing sets using train_test_split from scikit-learn.
4. **Training the Model**: A Multiple Linear Regression model is trained using the training data.
5. **Making Predictions**: The trained model is used to make predictions on the test data.
6. **Testing Accuracy**: The accuracy of the model is evaluated using the R-squared score, which measures how well the model explains the variability of the target variable.

## Results
The R-squared score obtained on the test set is approximately 0.872, indicating a good fit of the model to the data.

For more details, please refer to the Jupyter notebook or Python script provided in this repository.
