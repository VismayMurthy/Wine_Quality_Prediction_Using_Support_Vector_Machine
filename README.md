# Wine_Quality_Prediction_Using_Support_Vector_Machine
## Overview

This project predicts the quality of white wine using Support Vector Machine (SVM) classification. The dataset includes various chemical properties of the wine, which are used as features to predict its quality.

## Dataset Information

The white wine dataset contains twelve variables:
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

13. ## Dependencies

- pandas
- numpy
- scikit-learn

- ## Results

### Initial Model Evaluation

The initial SVM model was evaluated using a confusion matrix and classification report, providing insights into its accuracy and performance.
### Binary Classification

Wine qualities were re-labeled into two classes:
1. Quality 3, 4, 5 labeled as 0
2. Quality 6, 7, 8, 9 labeled as 1

The SVM model was retrained and evaluated for binary classification, showing improved performance.
