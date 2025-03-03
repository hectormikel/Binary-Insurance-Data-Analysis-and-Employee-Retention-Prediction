# Binary-Insurance-Data-Analysis-and-Employee-Retention-Prediction

This repository contains a Jupyter Notebook that performs data analysis and builds predictive models using logistic regression. The notebook focuses on two datasets: insurance purchase data and employee retention data.

## Overview

The notebook is divided into two main sections:

1. **Insurance Data Analysis**:
   - Loads and visualizes insurance data.
   - Builds a logistic regression model to predict whether a person bought insurance based on their age.

2. **Employee Retention Analysis**:
   - Loads and preprocesses HR data.
   - Conducts exploratory data analysis (EDA) to identify patterns related to employee retention.
   - Builds a logistic regression model to predict employee retention based on various features.

## Key Features

- **Data Loading**: Uses `polars` to read CSV files efficiently.
- **Visualization**: Utilizes `matplotlib` for data visualization.
- **Model Building**: Implements logistic regression models using `scikit-learn`.
- **Data Preprocessing**: Handles missing values and performs feature encoding.
- **Exploratory Data Analysis (EDA)**: Provides insights into the data through descriptive statistics and visualizations.

## Dependencies

- `polars`: For efficient data manipulation.
- `pandas`: For additional data manipulation tasks.
- `matplotlib`: For data visualization.
- `scikit-learn`: For machine learning model building and evaluation.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
