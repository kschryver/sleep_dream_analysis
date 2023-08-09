# Sleep and Dream Analysis

## Introduction
This repository contains an analysis of sleep and dream data using Python. The project explores the relationships between sleep hours, dream metrics, and overall day ratings. The analysis involves basic statistics, data visualization, and machine learning using various regression models. The goal is to predict overall day ratings based on sleep hours and dream metrics.

## Features
- Data preprocessing and basic statistics
- Correlation analysis between sleep hours, dream metrics, and overall day ratings
- Data visualization using Seaborn and Matplotlib
- Machine learning with Linear Regression, Random Forest Regressor, and Support Vector Regressor

## Getting Started
Clone the repository:

```git clone https://github.com/your-username/sleep-and-dream-analysis.git```

```cd sleep-and-dream-analysis```

Install the required dependencies (Pandas, Seaborn, Matplotlib, Scikit-Learn) using pip:

```pip install pandas seaborn matplotlib scikit-learn```

## Usage
1. Open and run the Jupyter Notebook Sleep_and_Dream_Analysis.ipynb to perform the analysis and visualization steps.
2. Follow the instructions and comments in the Notebook to understand each step of the analysis.
3. Experiment with different machine learning models, feature engineering, and data transformations to improve model performance.

## Results
The project's analysis and machine learning models produced the following results:
- Linear Regression:
Mean Squared Error: 0.52
R-squared Score: -0.08
- Random Forest Regressor:
Mean Squared Error: 2.32
R-squared Score: -3.85
- Support Vector Regressor:
Mean Squared Error: 0.55
R-squared Score: -0.15
The results indicate that none of the models performed well in explaining the variance in the target variable. Additional analysis and model tuning may be required to achieve better predictive performance.

Dependencies
- Python 3.6+
- Pandas
- Seaborn
- Matplotlib
- Scikit-Learn
