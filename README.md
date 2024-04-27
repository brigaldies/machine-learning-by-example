# Content

This repo contains a variety of machine learning examples.

Current examples are for:
- Regression
  - Linear Regression
    - Single-Variable Linear Regression
    - Multi-Variable Linear Regression
  - Polynomial Regression
    - Single-Variable Polynomial Regression
    - Multi-Variable Polynomial Regression
- Neural Networks
  - Vector Operations
  - Simple neural network, with gradient descent

The repo was created in April 2024.

# Python Runtime Environment Setup

- Install pipx
```shell
brew install pipx
```

- Install poetry
```shell
pipx install poetry
pipx ensurepath
```

- Configure Poetry to create the virtual Python runtime at the project's root. \
This allows IDEs such as PyCharm to easily find and use the environment, which then allows you to run the Jupyter notebooks within the IDE.
```shell
export POETRY_VIRTUALENVS_IN_PROJECT=true
```

- Install the Poetry project
```shell
poetry install
```

# Regression

## Linear Regression

### Single-Variable Linear Regression

The example in the `single-variable-linear-regression` Jupyter notebook provides a linear regression with a single input 
(aka, dependent, predictor, or feature) variable.

### Multi-Variable Linear Regression

The example in the `multiple-variable-linear-regression` Jupyter notebook provides a linear regression with multiple input 
(aka, dependent, predictor, or feature) variables.

## Polynomial Regression

### Single-Variable Polynomial Regression

The example in the `single-variable-polynomial-regression` Jupyter notebook provides a polynomial regression with a single input 
(aka, dependent, predictor, or feature) variable.

### Multi-Variable Polynomial Regression

The example in the `multiple-variable-polynomial-regression` Jupyter notebook provides a polynomial regression with multiple input 
(aka, dependent, predictor, or feature) variables.

# Neural Network

## Vectors and Dot-Products

The example in the `vectors-and-weights` Jupyter notebook provides examples of vectors, and the vectors "dot product" operation.

## Simple Neural Network

The example in the `my-first-neural-network` Jupyter notebook provides an example of a simple neural network with 
a gradient descent calculation to update the weights and decrease the loss function.