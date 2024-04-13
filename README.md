# Content

This repo contains a variety of machine learning examples.

Current examples are for:
- Regression
  - Linear Regression
    - Single-Variable Linear Regression
    - Multi-Variable Linear Regression

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