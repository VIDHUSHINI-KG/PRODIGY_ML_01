## PRODIGY_ML_01
This project uses a Random Forest Regressor to predict house prices based on various features such as the number of bedrooms, bathrooms, area, floors, garage, condition, location, and year built.

## Dataset
The dataset used for training is `house_price.csv`. It includes the following features:
- **Bedrooms**: Number of bedrooms in the house
- **Bathrooms**: Number of bathrooms
- **Area**: Total area of the house
- **Floors**: Number of floors
- **Garage**: Garage availability
- **Condition**: House condition rating
- **Location**: Geographic location of the house
- **YearBuilt**: Year the house was built
- **Price**: Target variable (house price)
  
- ## Model
  The script uses a RandomForestRegressor from sklearn.ensemble to train the model on the dataset. The dataset is split into training and test sets using train_test_split.
- ## Evaluation Metrics
- The model is evaluated using:- Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
- R-squared (R²): Indicates the goodness-of-fit of the regression model.
  ## Visualization
  The script generates a scatter plot comparing actual vs. predicted house prices.
  ## Dependencies
  Ensure you have the following installed:- pandas
- numpy
- matplotlib
- scikit-learn
- ## License
  This project is licensed under the MIT License.

