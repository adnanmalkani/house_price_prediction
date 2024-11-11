# House Price Prediction Project 🏡💻

Welcome to the **House Price Prediction** project! This repository contains code for predicting house prices using **Multiple Linear Regression** and **Decision Tree Regression** models. The project was completed as part of the **Atomcamp Machine Learning Bootcamp**.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Key Learnings](#key-learnings)
- [Contributors](#contributors)

---

## Overview

This project explores how to predict house prices based on features like:
- **Square Footage**
- **Number of Bedrooms**
- **House Age**

Two regression models were built and compared:
1. **Linear Regression**
2. **Decision Tree Regression**

In addition, I examined the impact of **scaling** the data using **StandardScaler** and how it affects model performance and feature importance.

## Features
- Data visualization to explore relationships between house prices and features.
- Implementation of Multiple Linear Regression and Decision Tree Regression.
- Model evaluation using **Mean Squared Error (MSE)** and **R² score**.
- Feature importance analysis to determine which features contribute the most to the model's predictions.
- Impact of feature scaling on model performance.

## Technologies Used
- **Python**: Programming language
- **pandas**: For data manipulation
- **matplotlib** & **seaborn**: For data visualization
- **scikit-learn**: For model building and evaluation
- **Jupyter Notebook**: For interactive coding

## Getting Started

Follow the instructions below to get a copy of the project up and running on your local machine.

### Prerequisites

You'll need to have the following installed on your machine:
- **Python 3.6+**
- **Jupyter Notebook**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd house-price-prediction
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
2. Run through the notebook cells to explore the dataset, train the models, and evaluate their performance.

3. To view the data visualizations and results, execute all cells in the notebook.

## Results

- **Linear Regression** achieved an R² score of **0.997** on the test data, indicating a strong performance.
- **Decision Tree Regression** showed a lower R² score compared to Linear Regression.
- After scaling the data, the importance of features shifted, with **Square Footage** becoming the most dominant feature.

## Key Learnings

- Feature scaling can significantly affect model performance, especially for algorithms like Linear Regression.
- **Square Footage** and **Number of Bedrooms** were the most important features, but their contributions became clearer after scaling.
- Visualizing data before modeling is crucial for understanding relationships and choosing the right preprocessing steps.

## Contributors

- **Your Name** - [GitHub Profile](https://github.com/yourusername)
- **Mahnoor Salman** (Instructor at Atomcamp) - For excellent guidance and teaching!

