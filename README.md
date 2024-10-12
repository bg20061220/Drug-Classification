# Drug Classification Challenge

## Overview
In this project, I tackled a drug classification challenge using an One-vs-Rest (OvR) Logistic Regression model. The goal was to accurately classify different drugs based on their features.

## Data Preprocessing
Prior to training the model, several preprocessing steps were undertaken to prepare the data for analysis:

1. **Data Cleaning**
   - Removed any irrelevant or redundant data to ensure the quality of the dataset.
   - Handled missing values appropriately to maintain the integrity of the dataset.

2. **Encoding**
   - Categorical variables were transformed into numerical format using encoding techniques. This step is crucial for enabling the model to interpret the features effectively.

3. **Normalization**
   - Normalized the data to ensure that all features contribute equally to the distance calculations in the model.

## Model Training
- I utilized the One-vs-Rest (OvR) strategy with the Logistic Regression algorithm to handle the multi-class classification problem. 
- Hyperparameter tuning was performed to optimize the model's performance.

## Results
After completing the preprocessing steps and training the model, I achieved an impressive **97.5% accuracy** on the classification task. This high level of accuracy indicates that the model can effectively distinguish between the different drug classes based on the provided features.

## Conclusion
The project demonstrated the importance of thorough data preprocessing, appropriate model selection, and hyperparameter tuning in achieving high accuracy in classification tasks. The OVR Logistic Regression model proved to be effective for the drug classification challenge.
