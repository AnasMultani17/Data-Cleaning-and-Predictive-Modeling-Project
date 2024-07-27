Sure! Here’s how you can include the link to your repository in the README file. I've updated the `Usage` section to reflect the correct repository URL.

---

# Wine Quality Prediction

## Overview

This project aims to predict wine quality based on various chemical attributes. The dataset contains 1599 samples with 12 columns, including 11 chemical properties and one quality rating. The primary objectives include data preprocessing, statistical analysis, visualization, and predictive modeling.

## Table of Contents

- [Project Description](#project-description)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Statistical Analysis](#statistical-analysis)
- [Visualization](#visualization)
- [Modeling](#modeling)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Project Description

The dataset consists of 11 chemical attributes and a quality score ranging from 3 to 8. The project involves:

1. Handling missing values.
2. Performing statistical analysis.
3. Visualizing data relationships.
4. Training and evaluating machine learning models.

## Data

- **File Name**: `winequality-red.csv`
- **Number of Samples**: 1599
- **Features**:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol
  - Quality (target variable)

## Preprocessing

1. **Null Value Handling**: Replaced missing values in numerical columns with the mean and in categorical columns with the mode.
2. **Data Cleaning**: Removed records with null values and imputed missing data as necessary.

## Statistical Analysis

Performed statistical operations on the dataset, including:
- Count
- Sum
- Range
- Minimum
- Maximum
- Mean
- Median
- Mode
- Variance
- Standard Deviation

## Visualization

Utilized various plots to visualize the data:
- Scatter Plots
- Line Graphs
- Histograms

These visualizations help in understanding the relationships between different chemical attributes and wine quality.

## Modeling

- **Algorithms Used**: K-Nearest Neighbors (KNN) Classifier and Regressor
- **Train-Test Split**: 80% training data and 20% testing data
- **Evaluation Metrics**: Accuracy, Mean Squared Error (MSE)

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/AnasMultani17/Data-Cleaning-and-Predictive-Modeling-Project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Data-Cleaning-and-Predictive-Modeling-Project
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis and modeling:
   ```bash
   python main.py
   ```

## Contributors

- **Anas Multani**
- **Devan Modhavadiya**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
