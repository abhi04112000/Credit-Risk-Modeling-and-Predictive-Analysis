# Credit Risk Modeling and Predictive Analysis

## Project Overview

This project involves developing and evaluating credit risk models to classify customer loan eligibility based on a comprehensive dataset. The analysis includes feature engineering, hypothesis testing, and the application of various machine learning models and techniques to enhance predictive performance.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The Credit Risk Modeling project focuses on classifying customer loan eligibility using a dataset of 51,336 customers with 79 features. The project encompasses feature engineering, hypothesis testing, handling imbalanced data, and developing predictive models. The goal is to accurately predict credit risk and improve model performance using advanced techniques.

## Features

- **Data Analysis:** Analyzed a dataset with 51,336 customers and 79 features to classify loan eligibility.
- **Feature Engineering (FE):** Performed feature engineering to improve model performance.
- **Hypothesis Testing:** Used Chi-Square tests, ANOVA, and Sequential VIF for hypothesis testing and feature selection.
- **Handling Imbalanced Data:** Applied SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance.
- **Distribution Comparison:** Used Kolmogorov–Smirnov test to compare distributions and enhance model performance.
- **Model Development:** Developed credit risk models using Logistic Regression (One-vs-Rest), Random Forest, and XGBoost.
- **Hyperparameter Tuning:** Implemented hyperparameter tuning using the Optuna framework.
- **Performance:** Achieved an accuracy of 80% with XGBoost.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** scikit-learn, XGBoost, Optuna, imbalanced-learn
- **Statistical Tests:** Chi-Square, ANOVA, Kolmogorov-Smirnov, Sequential VIF
- **Techniques:** SMOTE, Logistic Regression, Random Forest, XGBoost

## Methodology

### Data Analysis

- **Dataset:** Analyzed a masked dataset of 51,336 customers with 79 features to classify loan eligibility.

### Feature Engineering and Hypothesis Testing

- **Feature Engineering:** Enhanced feature set through various techniques.
- **Hypothesis Testing:** Applied Chi-Square tests, ANOVA, and Sequential VIF for feature selection and hypothesis testing.
- **Data Balancing:** Used SMOTE to handle class imbalance and ensure better model training.

### Model Development

- **Logistic Regression:** Implemented One-vs-Rest (OVR) logistic regression for initial classification.
- **Ensemble Techniques:** Developed models using Random Forest and XGBoost for improved accuracy and robustness.

### Hyperparameter Tuning

- **Optuna Framework:** Applied Optuna for hyperparameter tuning to optimize model performance.

## Results

- **Model Accuracy:** Achieved an accuracy of 80% using the XGBoost model.
- **Enhanced Performance:** Improved model performance through feature engineering, hypothesis testing, and hyperparameter tuning.

## Usage

1. **Setup:** Ensure all required libraries and dependencies are installed.
2. **Data Preparation:** Load and preprocess the dataset, including feature engineering and handling imbalanced data with SMOTE.
3. **Model Training:** Train models using Logistic Regression, Random Forest, and XGBoost.
4. **Hyperparameter Tuning:** Use Optuna to fine-tune model hyperparameters.
5. **Evaluation:** Evaluate model performance and select the best-performing model based on accuracy and other metrics.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
