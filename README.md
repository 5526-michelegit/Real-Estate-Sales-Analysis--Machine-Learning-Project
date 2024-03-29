# King County Real Estate Price Prediction

This project is focuses on predicting real estate prices in King County, Washington, using various machine learning models. The dataset includes transactions from May 2014 to May 2015, a period marked by the recovery from the housing crisis that began in 2006.

## Project Overview

### Objective
To analyze and predict real estate prices using supervised learning models, including linear regression, regression trees, and neural networks, identifying key features that influence property prices.

### Dataset
The dataset comprises 21,613 instances and 21 attributes, covering a wide range of property characteristics such as the number of bedrooms, bathrooms, living space square footage, and location details.

### Methodology

#### Preprocessing
Key preprocessing steps included outlier removal, attribute transformation, and handling of multicollinearity. Notable adjustments included the conversion of certain variables to binary to enhance model performance and data interpretability.

#### Models Deployed
- **Linear Regression (Simple, Multiple, Polynomial)**
- **Regression Trees (Simple and Ensemble Methods)**
- **Random Forest and Gradient Boosted Trees**
- **Multilayer Perceptron (Neural Network)**

Each model was evaluated using Holdout and Cross-Validation methods to ensure robustness and accuracy.

#### Clustering
Implemented K-means and K-medoids clustering to analyze property groups, utilizing silhouette coefficient and entropy for evaluation.

## Tools and Libraries Used
- **Python** for data manipulation and model development.
- **KNIME** and **R** for preprocessing and analysis.
- **Scikit-learn** for machine learning models.
- **Weka** for certain model implementations.

## Results
The project successfully applied various regression models, with tree-based models and the Multilayer Perceptron showing the most promise based on Holdout and Cross-Validation methods. These models achieved satisfactory prediction accuracy, highlighting the potential of machine learning in real estate price estimation.

## Future Directions
Future work could focus on feature selection to enhance model performance and further exploration of model parameters. Additionally, alternative research questions and variable combinations could yield further insights.

For more detailed information on our methodology, findings, and conclusions, please refer to the full project documentation included in this repository.
