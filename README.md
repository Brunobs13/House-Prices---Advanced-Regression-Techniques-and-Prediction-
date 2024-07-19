# House Prices Regression Analysis

## Overview

This project aims to predict house prices using a range of regression models. The dataset used is from the Kaggle competition "House Prices: Advanced Regression Techniques". The goal is to build and evaluate multiple regression models, blend their predictions, and generate a final submission for the competition.

## Project Structure

- **Data Preprocessing**: Clean and preprocess the data, including handling missing values and feature engineering.
- **Model Training and Evaluation**: Train and evaluate various regression models using cross-validation.
- **Blending Predictions**: Combine predictions from multiple models to improve accuracy.
- **Submission**: Generate predictions for the test set and prepare them for submission.

## Files

- `data_preprocessing.py`: Contains code for data cleaning and feature engineering.
- `model_training.py`: Contains code for training and evaluating regression models.
- `submission.py`: Contains code for generating predictions and preparing the submission file.
- `resultados_validacao_cruzada.csv`: CSV file containing the results of cross-validation for different models.
- `submission_regression.csv`: CSV file with the final predictions for the test set.

## Dependencies

Ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `lightgbm`
- `xgboost`
- `catboost`

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn lightgbm xgboost catboost
```

## Conclusion
The project successfully implements a range of regression models and blends their predictions to achieve better performance. The final predictions are saved in submission_regression.csv and submission.csv for submission to the Kaggle competition.
