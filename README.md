# Elevate-Labs-Task-3-Linear-Regression
# Steps Performed

1. **Data Loading**  
   A small dataset of house listings was manually loaded into a pandas DataFrame.

2. **Feature-Target Split**  
   - `X`: All features except `price`  
   - `y`: Target variable `price`

3. **Z-score Normalization**  
   Standardization of all features was done using `StandardScaler` from `sklearn.preprocessing` to bring them to a common scale (mean = 0, std = 1).

4. **Train-Test Split**  
   Data was split into training and test sets using `train_test_split()` with a test size of 25%.

5. **Model Training**  
   A Linear Regression model was trained using `sklearn.linear_model.LinearRegression`.

6. **Model Evaluation**  
   Evaluation was done using the following metrics:
   - **MAE (Mean Absolute Error)**
   - **MSE (Mean Squared Error)**
   - **R² Score**

7. **Visualization**  
   A scatter plot was created to compare actual vs predicted house prices based on the `area` feature.



