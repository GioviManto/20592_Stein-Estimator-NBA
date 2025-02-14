# 20592_Stein-Estimator-NBA

## Overview
This repository contains an analysis of the James-Stein estimator applied to NBA player data. The James-Stein estimator is a shrinkage estimator that dominates the Maximum Likelihood Estimator (MLE) in dimensions greater than or equal to 3, leading to improved estimation accuracy.

## Files in This Repository
- **`final_dataset_master.csv`**: The dataset containing NBA player statistics used for the analysis.
- **`James_Stein_Estimator_NBA_Analysis.ipynb`**: Jupyter Notebook implementing the James-Stein estimator on NBA player data.
- **`Stein's Estimator Application.pdf`**: A detailed report explaining the methodology, results, and conclusions of the analysis.

## Methodology
1. **Exploratory Data Analysis (EDA):**  
   - The dataset was examined to understand the distribution of height and weight across different player positions.  
   - Players were grouped into positions: PG, SG, SF, PF, and C.  

2. **Estimation Process:**  
   - The MLE was computed for each player position based on sample data.  
   - The James-Stein estimator was applied to shrink estimates toward the overall mean.  

3. **Performance Evaluation:**  
   - The Mean Squared Error (MSE) of both estimators was compared to determine the improvement provided by the James-Stein estimator.  

## Results
The James-Stein estimator demonstrated lower MSE compared to MLE, supporting its theoretical advantage in higher dimensions.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/GioviManto/20592_Stein-Estimator-NBA.git


Open `James_Stein_Estimator_NBA_Analysis.ipynb` in Jupyter Notebook and run the cells to reproduce the analysis.


## References

James, W., & Stein, C. (1961). Estimation with Quadratic Loss.



Data sourced from Kaggle NBA player statistics.

