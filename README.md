# Decision Tree Regressor - California Housing Prices Prediction

## Overview

This project implements a **Decision Tree Regressor** model to predict housing prices in California based on various features. The dataset used is the **California Housing** dataset from Scikit-learn, which contains features such as median income, housing age, and the number of rooms in each block of California. The goal is to predict the median house value for California districts, using a Decision Tree model.

## Key Features

- **Model**: Decision Tree Regressor
- **Dataset**: California Housing dataset
- **Performance Metrics**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)

## Setup

1. Clone the repository or download the code.
2. Install the required libraries using:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script `dtr_california_housing.py` to train and test the model.

## Features

- **Data Preprocessing**: The dataset is split into training and testing sets (80%/20%), and the features are standardized using `StandardScaler`.
- **Model Training**: A Decision Tree Regressor is trained on the scaled data.
- **Model Evaluation**: The model is evaluated using MSE, RMSE, and R².
- **Learning Curve Plot**: A learning curve is plotted to analyze model performance across different training data sizes.

## Results

- **MSE**: 0.49
- **RMSE**: 0.70
- **R²**: 0.62

## Plotting

- **Learning Curve Plot**: Shows model performance as the training size increases.
- **Feature Importance Plot**: Visualizes the importance of each feature in predicting the target variable.

## Conclusion

The model performs well with an R² of 0.62, indicating that 62% of the variance in housing prices is explained. However, there is room for improvement by addressing overfitting and experimenting with alternative models like Random Forest or Gradient Boosting.

## License

This project is licensed under the MIT License.

---

You can save this as `README.md` in your project directory! Let me know if you want to add or modify any details.
