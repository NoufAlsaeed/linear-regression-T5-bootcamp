

**Predicting car prices using linear regression**

# **Abstract:**
Lots of people renovate and sell their cars.  But they face the problem of determining the car's selling price based on the specifications of their cars. To help them determine the expected price for their cars, we used the data from cars.com and we build the linear regression model to predict the prices of cars.
# **Design:**
This project originates from the Data Science Bootcamp (T5) to predict car prices by using Cars.com dataset through Linear Regression. 
# **Data:**
Using Cars.com dataset and filtered the results to get Honda cars only, the dataset contained 400 observations and about 6 features: **DESCRIPTION, DEALER, MILES\_DRIVEN, RATE, NO\_OF\_REVIEWS, and PRICE,** where **DESCRIPTION** and **DEALER** are object data types, and the other columns are integer and float datatypes, and we added feature engineering. 
# **Algorithms:**
## **Feature engineering:** 
- **MODEL: Model year of each car.**
- **CAR\_NAME: The name of the car.**
- **CAR\_NAME\_Other: The name of the car that is repeated less than 25 times.**
## **Preprocessing:** 
- **Check if there are any missing values**
- **Check if there are any duplicate values**
- **Creating Dummy Variables.**
- **Convert the DataType of the MODEL.**
- **Feature Scaling.**
## **Visualization:**
- **Histogram plot: to show the Count of Cars by Price.** 
- **Distplot: to represent the Density or Relative Frequency of Cars by Price.** 
- **Pairplot: to shows the relationship for (n, 2) combination of features in a DataFrame.** 
- **Heatmap: to show the correlation between the features.** 
# **Tools:**
- Pandas and NumPy packages to manipulate data.
- Matplotlib and seaborn library for visualizing data.
- BeautifulSoup library and requests for pulling data out of the Cars.com website.
- LinearRegression from the sklearn.linear\_model class of the sklearn module, to perform the linear regression then predicted the price.
- Lasso from the sklearn.linear\_model class of the sklearn module, to perform the Lasso regression then predicted the price.
- Ridge from the sklearn.linear\_model class of the sklearn module, to perform the Ridge regression then predicted the price.
- mean\_squared\_error from the sklearn.metrics module to measures the average squared difference between the estimated values and actual value.
- mean\_absolute\_error from the sklearn.metrics module to measure the accuracy of the model.
- Diagnostic library to plot assumption 1 which is regression is linear in parameters and correctly specified
- Metrics library to see the model performance on data. 
- StandardScaler and scale library to removes the mean and scales each feature/variable to unit variance.
- Statsmodels to explore data, estimate statistical models, and perform statistical tests.
- scipy.stats for obtaining probabilistic distributions and generate random numbers.
- cross\_val\_score to perform the evaluation, taking the dataset and cross-validation configuration and returning a list of scores calculated for each fold. 
- train\_test\_split to split the training and test data sets. 
- Jupyter notebook to execute the code.

# **Communication**
Presentation.


` `PAGE   \\* MERGEFORMAT 2

