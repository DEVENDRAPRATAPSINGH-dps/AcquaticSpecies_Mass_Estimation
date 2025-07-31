# Fish Weight Prediction using Linear Regression

This project models and predicts the **weight of fish** (in grams) from their physical biometrics using a simple, interpretable **Linear Regression** approach. Given measurements like vertical, diagonal, and cross lengths, along with height and width, the aim is to understand and quantify how these size features relate linearly to the fish’s weight.

## Dataset Features

- **Species**: Categorical name of the fish species (used for encoding or grouping).  
- **Weight**: Target variable — fish weight in grams.  
- **Length1**: Vertical length in cm.  
- **Length2**: Diagonal length in cm.  
- **Length3**: Cross length in cm.  
- **Height**: Height in cm.  
- **Width**: Diagonal width in cm.  

## Summary

The pipeline includes data preprocessing (handling species encoding and any missing values), exploratory analysis to inspect correlations and multicollinearity, fitting an ordinary least squares Linear Regression model, and evaluating it with metrics like R² and RMSE. Coefficients are examined to interpret feature influence on weight. The goal is both predictive and diagnostic: to see how well weight can be approximated linearly and which physical attributes drive that relationship.
