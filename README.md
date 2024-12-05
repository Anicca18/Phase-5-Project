# Phase-5-Project
# Bitcoin Price Prediction Model

## Overview

This project aims to predict the likelihood of a price increase for various tokens using historical data. The model leverages machine learning techniques to analyze features such as price variations, market capitalization, and token supply. The primary goal is to provide insights into which tokens are most likely to experience a price increase, aiding investors in making informed decisions.

## Project Structure

- **Data Collection**: The dataset is sourced from a CSV file containing historical token data.
- **Feature Engineering**: Key features are selected to avoid data leakage and ensure robust predictions.
- **Model Training**: Multiple machine learning models are trained and evaluated, including Random Forest, Logistic Regression, SVM, Neural Network, and Gradient Boosting.
- **Model Evaluation**: Models are evaluated based on accuracy and cross-validation scores, with a focus on the Gradient Boosting model.

## Gradient Boosting Model Metrics

The Gradient Boosting model is one of the key models used in this project. It is evaluated using the following metrics:

- **Accuracy**: Measures the proportion of true results (both true positives and true negatives) among the total number of cases examined.
- **Cross-Validation Score**: Provides an average performance measure across multiple folds of the dataset, ensuring the model's robustness.
- **Confusion Matrix**: Visualizes the performance of the model by showing the true positive, true negative, false positive, and false negative predictions.

### Confusion Matrix for Gradient Boosting Model

The confusion matrix for the Gradient Boosting model is displayed to provide a detailed view of the model's performance. It helps in understanding the types of errors the model is making and the balance between precision and recall.

## Usage

1. **Data Preparation**: Ensure the dataset is available in the specified path.
2. **Model Training**: Run the notebook to train the models and evaluate their performance.
3. **Prediction**: Use the best-performing model to predict the probability of price increases for new tokens.

## Results

The project outputs a detailed analysis of the top tokens most likely to increase in price, along with a report that includes the number of holders, market cap, and other relevant metrics. The results are visualized through various plots, including feature importance and model comparison.

## Conclusion

This project provides a comprehensive approach to predicting token price increases using machine learning. The Gradient Boosting model, in particular, offers a reliable method for making these predictions, supported by robust evaluation metrics.