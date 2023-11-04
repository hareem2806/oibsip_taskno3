# oibsip_taskno3
CAR PRICE PREDICTION DATASET 

Overview:
This project aims to predict the selling price of cars based on various features such as car name, fuel type, transmission type, and more. It uses machine learning techniques, particularly Linear Regression, to make predictions. The project includes data preprocessing, exploratory data analysis (EDA), label encoding, and model building.

Preprocessing:
The data is loaded and file is read. Inconsistency in data is checked by checking for null and duplicate values. Moreover some inapprpriate column names are renamed.

Exploratory Data Analysis:
The code also includes some exploratory data analysis (EDA) to understand the car_data.csv dataset. The following observations can be made from the EDA:

* The car name City has the highest count.
* The distribution of selling price and present price is positively skewed.
* Most of the cars in the dataset are petrol cars, have dealer as their selling type, and have manual transmission.

Label Encoding:
The code also performs label encoding on the categorical features (Transmission, Fuel_Type, and Selling_Type) to convert them into numerical representation. This is required because linear regression models can only work with numerical data.

Splitting the Data:
The data is split into training and test sets using the train_test_split() function from scikit-learn. The training set is used to train the linear regression model, and the test dataset is used to evaluate its performance.

Model Evaluation:
Firstly, the model is evaluated on the test set using scatter plot visualization. A plot between actual and predicted values is made.

Then the model is evaluated on the test set using the following metrics:

Accuracy: The percentage of predictions that are correct.
R-squared: A measure of how well the model fits the data.
Mean absolute error (MAE): The average difference between the predicted and actual values.
Mean squared error (MSE): The average squared difference between the predicted and actual values.

Conclusion
The linear regression model achieves an accuracy of 83.65% on the test dataset.
