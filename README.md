# exoplanet-exploration

## Machine Learning Homework

### Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, we will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

### Instructions
* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use MinMaxScaler to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters
* Use GridSearch to tune model parameters.
* Tune and compare at least two different classifiers.

### Process

* In the first step, I assigned the koi_disposition as y (target) value and the rest columns as X (features).
* Next, I scaled and encoded the X and y values, then split them into training and testing data.

### Tuning the models
* Using GridSearchCV to tune the model's parameters and changing the grid parameters

### Analysis
* Logistic Regression model: Training Data Score = 0.84588 / Testing Data Score = 0.87850 (Tuned)
* SVM model: Training Data Score = 0.83730 / Testing Data Score = 0.86610 (Tuned)
* Random Forest model: Training Data Score = 1.0 / Testing Data Score = 0.89185

### Model Selection

Comparing all three models, the random forest yielded the highest score after hypterparameters tuning. Therefore, the random forest model is better than the other three models.