# Bitcoin-Price-and-Fear-Greed-Index-Analysis

## Overview

This project aims to analyze the relationship between Bitcoin, the Fear and Greed Index, and the S&P 500. The main objective is to determine if there is a correlation between these modern and traditional investment tools and to explore the potential for future price prediction using machine learning methods.

## Project Proposal

In this project, we focus on:

- Analyzing the Bitcoin price, Fear and Greed Index, and the S&P 500 data set.
- Investigating the relationship between these datasets to see if they exhibit cyclical patterns over time.
- Utilizing data visualization techniques such as histograms and scatter plots to understand the distributions and relationships of these datasets.

## Data Sources

- Bitcoin price data
- Fear and Greed Index
- S&P 500 price data

## Machine Learning Models

### Phase 3: Building and Verifying ML Models

In this phase, two machine learning models were built and verified:

1. **k-Nearest Neighbors (kNN)**
2. **Decision Tree**

#### Steps Taken

1. **Data Preparation**
   - Loaded the dataset containing short-term fluctuations of Bitcoin price and Fear & Greed Index.
   - Split the data into features and target variables (Bitcoin price).

2. **Model Building**
   - Implemented and trained the kNN model with various hyperparameters.
   - Utilized Grid Search to find the optimal hyperparameters for the Decision Tree model.

3. **Model Verification**
   - Evaluated both models using the test set.
   - Calculated the Mean Squared Error (MSE) for each model.

#### Results

- **kNN Model**
  - Achieved lower MSE (0.04029) compared to the Decision Tree model.
  - Demonstrated better performance due to its ability to capture localized relationships and simpler decision boundaries.

- **Decision Tree Model**
  - Had a higher MSE (0.04447) compared to the kNN model.
  - Struggled to capture nuanced relationships in the data.

#### Conclusion

The kNN model outperformed the Decision Tree model for this dataset, indicating that kNN is better suited for capturing localized relationships between the features and the target variable in this context.

## Future Work

Future directions to enhance the predictive performance and interpretability of the models include:

- Leveraging advanced feature engineering techniques.
- Integrating additional data sources and temporal features.
- Optimizing model hyperparameters.
- Experimenting with ensemble methods such as stacking and blending.
- Delving into time series analysis, anomaly detection, and model interpretability methods.

These efforts will improve the accuracy and usability of predictive models, aiding decision-making in cryptocurrency markets.

