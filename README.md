# Maize-Yield-Prediction-Analysis

## Description
This project analyzes multi-year crop data to predict maize yield for 2008, using historical data from 2000-2007. The project compares two models: one trained on phenotypic and environmental data, and another adding genotypic information.


## Objective
The primary goals of this analysis are to:

1. Predict maize yield for 2008 using historical phenotypic, environmental, and genotypic data from previous years.
2. Evaluate the contribution of genotypic data by comparing the performance of two models: one based solely on phenotypic and environmental data, and another enhanced with genotypic features.

## Data Source and Description
This analysis is based on yield data shared by Bayer Crop Science for the hackathon, encompassing phenotypic, environmental, and genotypic information. Key columns include:
`year`, `loc`, `longitude`, `latitude`, `line`, `MST`, `TWT`, `YLD_BE`, and identifiers such as `germplasm_id`.

## Project Structure
The repository contains the following notebooks:</p>
`01_Data_Preprocessing.ipynb`: Data cleaning, handling missing values, and preprocessing for analysis.</p>
`02_EDA.ipynb`: Exploratory Data Analysis, including visualizations to uncover patterns and relationships in the data.</p>
`03_Model_Training.ipynb`: Model training, tuning, and evaluation, with a focus on comparing model performance with and without genotypic data.</p>
`04_Results_And_Visualizations.ipynb`: Presentation of final results, model performance metrics, and insights gained from the analysis.</p>

## Installation and Dependencies
To run this project, install the required dependencies with:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```
