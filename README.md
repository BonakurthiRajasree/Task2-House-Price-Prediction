# Task2-House-Price-Prediction
House Price Prediction using Machine Learning
# House Price Prediction

## Objective
Predict house prices using Machine Learning regression models.

## Dataset Features
- Bedrooms
- Bathrooms
- Living Area
- Lot Area
- Floors
- Waterfront
- View
- Condition
- Year Built
- City
- Street
- State

## Models Used
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

## Best Model
Random Forest Regressor

## Files
- Task2_House_Price_Prediction.ipynb
- house_price_model.pkl

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

## Example Prediction

```python
import joblib

model = joblib.load('house_price_model.pkl')
prediction = model.predict(sample_data)
print(prediction)
```
