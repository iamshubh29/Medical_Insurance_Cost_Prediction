# Insurance Cost Prediction 

# Overview

This project predicts insurance costs based on various input features, such as age, sex, BMI, children, smoker status, and region. The model was trained using historical insurance data to help individuals or insurance providers estimate potential costs for specific profiles.

## Features

The model takes in six input features:
1. **Age**: Age of the individual.
2. **Sex**: Gender of the individual (0 for female, 1 for male).
3. **BMI**: Body mass index, providing an understanding of weight category.
4. **Children**: Number of children covered by the insurance.
5. **Smoker**: Smoking status (0 for non-smoker, 1 for smoker).
6. **Region**: Area of residence (e.g., 0 for northeast, 1 for southeast, etc.).

The output is the estimated insurance cost in USD.

## Dependencies

- `numpy`: For data manipulation and transformation.
- `scikit-learn`: To load and use the machine learning model.

  
## Results
The model’s performance has been evaluated, and the following R-squared values were obtained:

1. R-squared (training data): 0.751505643411174.
2. R-squared (test data): 0.7447273869684077.
These values indicate that the model explains around 75% of the variance in the data.


