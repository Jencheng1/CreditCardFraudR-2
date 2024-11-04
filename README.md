

# Credit Card Fraud Detection with R

Welcome to the **Credit Card Fraud Detection with R** project repository! This project focuses on detecting fraudulent credit card transactions through machine learning models developed in R. The primary objective is to distinguish between legitimate and fraudulent transactions, contributing to enhanced financial security.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [License](#license)

## Project Overview

This repository includes an analysis and model implementation for identifying credit card fraud. The models are trained on a dataset of transaction records, aiming to improve fraud detection rates while minimizing false positives. The R programming language and libraries such as `tidymodels`, `dplyr`, and `ggplot2` are utilized for data preparation, model development, and evaluation.

## Installation

To use this project, ensure R is installed on your machine, along with the required R packages.

```R
install.packages(c("tidymodels", "dplyr", "ggplot2", "data.table", "caret", "xgboost"))
```

To clone this repository, use the following command:

```bash
git clone https://github.com/Jencheng1/CreditCardFraudR-2.git
cd CreditCardFraudR-2
```

## Dataset

The dataset used includes historical credit card transactions, with each transaction labeled as fraudulent or legitimate. The data is highly imbalanced, reflecting a real-world scenario where fraudulent transactions are rare.

> **Note**: You’ll need to download the dataset separately. You can find a suitable dataset on [Kaggle’s Credit Card Fraud Detection dataset page](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Usage

1. Clone the repository and open the notebook `credit-card-fraud-detection-using-r-programming.ipynb`.
2. Follow the steps in the notebook to load, preprocess, and analyze the data.
3. Run each cell sequentially to train and evaluate the machine learning models.

```bash
# Run Jupyter Notebook
jupyter notebook credit-card-fraud-detection-using-r-programming.ipynb
```

## Model Training

This project evaluates multiple machine learning models, including:

- Logistic Regression
- Decision Trees
- Random Forests
- XGBoost

The models are trained with cross-validation, and hyperparameters are tuned to improve accuracy. The notebook guides you through these processes with explanations of each step.

## Evaluation

The models are evaluated using key metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Area Under the Curve (AUC)

Visualizations like confusion matrices and ROC curves are provided to aid in the assessment of each model’s performance.

## License

This project is licensed under the MIT License. See the [LICENSE](https://www.mit.edu/~amini/LICENSE.md) file for more details.
