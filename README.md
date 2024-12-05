# Phase-5-Project

![bravenewcoin-memecoins-banner](https://github.com/user-attachments/assets/3b147aad-efa6-4edc-bcdf-fdbc9b11d7eb)

# Meme Coin Identifier and Price Prediction Model
## Author 
[Jessie Freelander](https://github.com/Anicca18)

## Overview

This project aims to identigy and predict the likelihood of a price increase for various tokens using historical data. The model leverages machine learning techniques to analyze features such as price variations, market capitalization, transaction frequency, and token supply. The primary goal is to provide insights into which tokens are most likely to experience a price increase, aiding investors in making informed decisions.

## Project Structure

- **Data Collection**: The dataset is sourced from dextools and etherscan's api after specifed wallet have been inputed.
- **Feature Engineering**: Key features are selected to avoid data leakage and ensure robust predictions.
- **Model Training**: Multiple machine learning models are trained and evaluated, including Random Forest, Logistic Regression, SVM, Neural Network, and Gradient Boosting.
- **Model Evaluation**: Models are evaluated based on accuracy and cross-validation scores, with a focus on the Gradient Boosting model.

## Gradient Boosting Model Metrics

The Gradient Boosting model was determined as the best model in this project. It is evaluated using the following metrics:

- **Accuracy**: 0.81
- **Precision**: 0.75
- **Recall**: 0.84
  Measures the proportion of true results (both true positives and true negatives) among the total number of cases examined.
- **Cross-Validation Score of different models**:
- ![Screenshot 2024-12-05 at 2 29 23 PM](https://github.com/user-attachments/assets/dddf9dfd-5b06-43a9-90e0-e51118f10b0b)
  Provides an average performance measure across multiple folds of the dataset, ensuring the model's robustness.


### Confusion Matrix for Gradient Boosting Model
  ![Screenshot 2024-12-05 at 2 28 46 PM](https://github.com/user-attachments/assets/22c3910b-b936-44bc-b021-3f28094e3dfe)

The confusion matrix for the Gradient Boosting model is displayed to provide a detailed view of the model's performance. It helps in understanding the types of errors the model is making and the balance between precision and recall.

## Usage

1. **Data Preparation**: Ensure the dataset is available in the specified path and attain acess to Dextool and Etherscan's API's.
2. **Model Training**: Run the notebook to train the models and evaluate their performance.
3. **Prediction**: Use the best-performing model to predict the probability of price increases for new tokens.

## Results

The project outputs a detailed analysis of the top tokens most likely to increase in price, along with a report that includes the number of holders, market cap, and other relevant metrics. The results are visualized through various plots, including feature importance and model comparison.
![Screenshot 2024-12-05 at 2 34 40 PM](https://github.com/user-attachments/assets/56eb1ef6-7d8c-4009-961c-81baa48a9fb0)


## Conclusion

This project provides a comprehensive approach to predicting token price increases using machine learning. The Gradient Boosting model, in particular, offers a reliable method for making these predictions, supported by robust evaluation metrics. Accuarcy can be increased by the utalization of more data, specifically on a minute by minute basis for price action. 

## Directory
Data: [Etherscan](https://etherscan.io/)
Data: [Dex Tools](https://www.dextools.io/app/en/new-tokens)
Presentation: [Presentation.pdf](https://github.com/user-attachments/files/18028688/Presentation.pdf)
