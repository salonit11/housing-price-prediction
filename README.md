# House Price Prediction

## Project Overview
This project predicts house prices using multiple regression models. The dataset contains numerical features such as area, number of bedrooms, and age of the house. We apply basic preprocessing and train different models to compare their performance.

## Dataset
- The dataset includes various numerical features like:
  - **Square footage**
  - **Total bedrooms**
  - **Total rooms**
  - **Household**
  - **Median Income**
  - **Ocean Proximity**
  - **Median house value**
- The target variable is **House Price** (continuous value).

## Data Preprocessing
1. **Handling Missing Values**
   - Filled missing values using the median.
2. **Feature Scaling**
   - Applied **StandardScaler** to normalize numerical features.

## Machine Learning Models Used
We trained and evaluated the following regression models:
1. **Linear Regression**
2. **Ridge Regression**
3. **Lasso Regression**
4. **Decision Tree Regressor**
5. **Support Vector Machine (SVM) Regressor**
6. **Random Forest Regressor**

## Model Evaluation
- Models were assessed using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**
- Performance comparison was based on test set results.

## Installation & Usage
### Requirements
```bash
pip install numpy pandas scikit-learn
```

### Run the Project
```bash
python house_price_prediction.py
```

## Results
| Model                  | R² Score |
|------------------------|----------|
| Linear Regression      | 47%    |
| Ridge Regression       | 61.6%    |
| Lasso Regression       | 61.6%    |
| Decision Tree          | 90%    |
| SVM                    | 75.5%    |
| Random Forest         | **96.4%**  |

## Conclusion
- **Random Forest achieved the highest accuracy.**
- **Feature scaling improved model performance.**
- **Regularization techniques (Ridge & Lasso) helped reduce overfitting.**

## Future Improvements
- Exploring deep learning models like Neural Networks.
- Adding more features such as location-based attributes.

---
🚀 *Happy Coding!*
