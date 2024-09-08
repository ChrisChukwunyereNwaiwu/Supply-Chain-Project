# Supply Chain Optimization Project

## Overview
This project uses data analysis and machine learning techniques to optimise supply chain operations. The objective is to develop a model that can predict key aspects of the supply chain, such as demand forecasting, inventory management, and efficient resource allocation. The dataset includes various features that influence supply chain performance, and the project aims to improve decision-making processes within this domain.

## Project Structure

- `Supplychain_Project_.ipynb`: This is the main Jupyter notebook containing all the steps involved in data analysis, preprocessing, model training, and evaluation.
- `Data`: Includes the datasets used for training and testing the models.
- `Models`: Contains trained machine learning models and scripts used to train them.
- `Visualizations`: Graphs and plots that show the results of the analysis and model performance.

## Key Features

- `Data Preprocessing`: Handling missing values, feature scaling, and feature engineering to prepare the data for modeling.
- `Exploratory Data Analysis (EDA)`: In-depth analysis of the data to identify patterns, correlations, and trends within the supply chain context.
- `Machine Learning Models`: Multiple models were trained and evaluated, including:
  - Linear Regression
  - Decision Trees
  - Random Forest
  - XGBoost
- `Evaluation Metrics`: Metrics such as RMSE, MAE, and R² are used to evaluate model performance.

## Installation and Setup

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or any preferred IDE that supports Jupyter notebooks.

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/ChrisChukwunyereNwaiwu/Supply-Chain-Project.git
    cd Supply-Chain-Project
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter notebook:
    ```bash
    jupyter notebook Supplychain_Project_.ipynb
    ```

## Usage
The notebook can be run step-by-step. It includes:
- Data loading and preprocessing
- Model training and evaluation
- Visualization of results

To adjust the models or the data, modify the notebook as necessary.

## Results
The model performance is evaluated based on the accuracy of predictions for different supply chain KPIs (Key Performance Indicators). The Random Forest model showed the highest accuracy with an R² score of 0.85 on the test set.

## Future Work
- Implement additional machine learning models to improve prediction accuracy.
- Integrate real-time data to allow dynamic decision-making within supply chain operations.
- Explore deep learning techniques for complex supply chain scenarios.

