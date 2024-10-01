# Predictive Modeling of GDP per capita

This repository contains code and resources for predicting GDP per capita using Ridge and Lasso regression techniques. The project includes data preprocessing steps, model building, evaluation metrics, and diagnostics for assessing model assumptions such as homoscedasticity.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The goal of this project is to develop predictive models for GDP per capita based on socio-economic indicators using Ridge and Lasso regression. These techniques are chosen for their ability to handle multicollinearity and perform variable selection, respectively.

## Data

- The dataset includes socio-economic indicators such as population, literacy rate, birth rate, and more.
- Features are preprocessed and standardized for modeling.
- Categorical variables like country and region are encoded using appropriate techniques.

## Methodology

- **Ridge Regression**: Implements regularization to mitigate multicollinearity.
- **Lasso Regression**: Performs feature selection by shrinking coefficients to zero.
- **Evaluation**: Metrics include R-squared, adjusted R-squared, and diagnostics for homoscedasticity using the Breusch-Pagan test.

## Results

- Models are evaluated on a testing dataset for performance and assumptions.
- Homoscedasticity is assessed, and potential corrections are discussed.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repository.git



