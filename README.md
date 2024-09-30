# World Happiness Report Analysis

This repository contains a full analysis of the World Happiness Report data. The analysis focuses on understanding the factors contributing to happiness across different countries and regions using Exploratory Data Analysis (EDA) and machine learning models.

## Project Overview

In this project, we:
- Performed data cleaning and handling of missing values
- Visualized data distributions and relationships between features
- Built predictive models using Linear Regression, Random Forest, and Gradient Boosting
- Tuned model hyperparameters and evaluated model performance using MSE and R² scores
- Analyzed feature importance to understand the key drivers of happiness

## Tools Used
- **Python**
- **Pandas, NumPy** for data manipulation
- **Matplotlib, Seaborn** for data visualization
- **Scikit-learn** for machine learning models
- **Folium** for geographical visualizations

## Dataset
The dataset is based on the [World Happiness Report](https://worldhappiness.report/). You can download the dataset from the official website.

## How to Run the Project

1. Clone this repository:
    ```bash
    git clone https://github.com/jnsouza/World-Happiness-Report-Analysis.git
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook World-Happiness-Analysis.ipynb
    ```

## Key Results

- The **Random Forest** model provided the best performance with the lowest MSE.
- The most important factors contributing to happiness are **Log GDP per capita**, **Social support**, and **Healthy life expectancy**.

## Conclusion
The analysis revealed significant insights into how economic and social factors influence happiness in different countries. The machine learning models allowed for the prediction of happiness scores based on these factors with reasonable accuracy.
