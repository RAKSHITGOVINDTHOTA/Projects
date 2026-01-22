# Used Car Price Prediction (Statistical Machine Learning)

## Overview
This project compares multiple regression models to predict used car prices
based on mileage and manufacturing year as part of STP 550 – Statistical Machine Learning.

## Dataset
- susedcars.csv
- Features: mileage, year
- Target: price (scaled in thousands)

## Models Implemented
- Decision Tree Regression (10 & 20 leaf nodes)
- Cost-Complexity Pruned Decision Tree
- Random Forest Regressor
- Gradient Boosting Regressor
- Neural Network (MLP)

## Evaluation Metric
- RMSE (Root Mean Squared Error)

## Results
| Model | RMSE |
|------|------|
| Gradient Boosting | **5.17** |
| Pruned Decision Tree | 5.64 |
| Random Forest | 5.64 |
| Decision Tree (10 leaves) | 5.69 |
| Decision Tree (20 leaves) | 6.13 |
| Neural Network | 9.72 |

Gradient Boosting achieved the best performance.

## Techniques Used
- Feature scaling
- Train-test split
- Model comparison
- Tree pruning (cost-complexity)
- Performance visualization

## Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Course
STP 550 – Statistical Machine Learning  
Arizona State University

## Authors
Rakshit Govind Thota  
Latika Liladhar Dekate
