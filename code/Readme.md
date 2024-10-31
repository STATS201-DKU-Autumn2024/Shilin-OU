## Overview
This code implements a linear regression model to analyze the impact of various features on the maximum weighted average cost of capital (maxwacc) in an energy sector dataset. The process begins by loading the dataset, selecting relevant features, and preprocessing the data to handle categorical variables and missing values. Afterward, the data is split into training and testing sets, and a linear regression model is trained using the pseudoinverse method, ensuring stability even in cases where the feature matrix is non-invertible. The model’s coefficients reveal the influence of each feature on maxwacc, providing insights into key factors affecting capital costs. Model performance is evaluated using Mean Squared Error (MSE) and R-squared (R²) to determine the accuracy and explanatory power. Finally, two visualizations—a feature impact bar chart and a linear regression fit plot—help illustrate the model’s insights and effectiveness.
## Purpose
The purpose of this code is to analyze the factors influencing the maximum weighted average cost of capital (maxwacc) in an energy dataset. It achieves this by training a linear regression model, evaluating model performance, and visualizing the impact of each feature to provide insights into key cost determinants.
## Result
The linear regression model results indicate a strong predictive performance, as evidenced by a low Mean Squared Error (MSE) and a high R-squared (R²) value, which suggest that the model accurately captures the relationship between selected features and the maximum weighted average cost of capital (maxwacc). The feature impact plot shows the coefficients for each predictor, highlighting the relative influence of factors such as Region, Scenario, and Energy Type on capital costs. Positive coefficients suggest an increase in maxwacc, while negative values indicate a decrease. The linear regression fit plot demonstrates a close alignment between predicted and actual values along a 45-degree line, indicating strong model fit. The residuals plot, which displays the errors between predicted and actual values, confirms that residuals are generally close to zero and randomly distributed, suggesting minimal bias and strong predictive power across different scenarios.

<img width="580" alt="image" src="https://github.com/user-attachments/assets/20912fdf-5026-4d3f-b963-8e47edbd2479">
<img width="608" alt="image" src="https://github.com/user-attachments/assets/7f879090-1f52-4c1d-a620-0641763b960f">
<img width="830" alt="image" src="https://github.com/user-attachments/assets/ba95f3d2-1cb1-4a99-9841-cdb1751a01e5">

## Note 
Detailed code in https://raw.githubusercontent.com/STATS201-DKU-Autumn2024/Week2-Shilin-OU/refs/heads/main/code/code.ipynb





