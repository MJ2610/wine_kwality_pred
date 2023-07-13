# wine_kwality_prediction using linear regression 
The task here is to predict the quality of red wine on a scale of 0–10 given a set of features as inputs. I have solved it as a regression problem using Linear Regression.

please install the following libraries using pip:-
* Pandas: pip install pandas
* matplotlib: pip install matplotlib
* numpy: pip install numpy
* scikit-learn: pip install scikit-learn

A brief description of code:
1. Finding correlations between each attribute of dataset using corr()
2. function get_features()which outputs only those features whose correlation is above a threshold value (passed as an input parameter to function).
3. Create training and testing set using train_test_split. 25% of the data is used for testing and 75% for training. You can check the size of the dataset using x_train.shape
4. Once the dataset is created, it is time to build your Linear Regression model. You can simply use the built-in function to create a model and then fit to training data. Once trained, coef_gives the values of the coefficients for each feature.
5. To predict the quality of wine with this model, use predict().
Finally the last output means:
* numbers mean that holding all other features fixed, a 1 unit increase in sulphates will lead to an increase of 0.8 in quality of wine, and similarly for the other features.
Also holding all other features fixed, a 1 unit increase in volatile acidity will lead to a decrease of 0.99 in quality of wine, and similarly for the other features.


