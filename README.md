# Maize-Yield-Prediction-Analysis

## Description
This project analyzes multi-year crop data to predict maize yield for 2008, using historical data from 2000-2007. The project compares two models: one trained on phenotypic and environmental data, and another adding genotypic information.


## Objective
The primary goal is to:

### 1. Predict yield for 2008 based on historical data.
### 2. Compare model performance using two approaches to understand the added value of genotypic data.

## Data Source and Description
This analysis is based on yield data shared by Bayer Crop Science for the hackathon, encompassing phenotypic, environmental, and genotypic information. Key columns include:
`year`, `loc`, `longitude`, `latitude`, `line`, `MST`, `TWT`, `YLD_BE`, and identifiers such as `germplasm_id`.

## Project Structure
The repository contains the following notebooks:
<p> `01_Data_Preprocessing.ipynb`: Data cleaning and preprocessing.</p>
<p> `02_EDA.ipynb`: Exploratory Data Analysis.</p>
<p> `03_Model_Training.ipynb`: Model training and tuning.</p>
<p> `04_Results_And_Visualizations.ipynb`: Results and visualizations.</p>

## Installation and Dependencies
To run this project, install the required dependencies with:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```
