Machine Learning in Python
===========================

## Contents
1. [Data Preprocessing](#data-preprocessing)
2. [Regression](#regression)
	1. [Simple Linear Regression](#simple-linear-regression)
	2. [Multiple Linear Regression](#multiple-linear-regression)
	3. [Polynomial Regression](#polynomial-regression)
	4. [Support Vector Regression](#support-vector-regression)
	5. [Decision Tree Regressor](#decision-tree-regressor)
3. [How to run the Python program](#how-to-run-the-python-program)

## Data Preprocessing

### Data Preprocessing

a.  [data_preprocessing.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/1_data_preprocessing/data_preprocessing.py)

* Taking care of missing data
* Encoding categorical data
* Splitting the dataset into the Training set and Test set
* Feature Scaling

Go to [Contents](#contents)

## Regression

### Simple Linear Regression

a.  [simple_linear_regression.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/1_simple_linear_regression/simple_linear_regression.py)

* Importing the dataset ([Salary_Data.csv](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/1_simple_linear_regression/Salary_Data.csv))
* Splitting the dataset into the Training set and Test set
* Fitting Simple Linear Regression to the Training set
* Predicting the Test set results
* Visualising the Training and Test set results

* Visualising the Training set results
![Visualising the Training set results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/1_simple_linear_regression/Visualising-the-Test-set-results.png)
* Visualising the Test set results
![Visualising the Training set results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/1_simple_linear_regression/Visualising-the-Test-set-results.png)

Go to [Contents](#contents)

### Multiple Linear Regression

a.  [multiple_linear_regression.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/2_multiple_linear_regression/multiple_linear_regression.py)

b. Multiple Linear Regression - Automatic Backward Elimination with p-values only: [backward_elimination_with_p_values_only.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/2_multiple_linear_regression/backward_elimination_with_p_values_only.py)

c. Multiple Linear Regression - Automatic Backward Elimination with p-values and adjusted R-squared: [backward_elimination_with_p_values_and_adjusted_r_squared.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/2_multiple_linear_regression/backward_elimination_with_p_values_and_adjusted_r_squared.py)

* Importing the dataset ([50_Startups.csv](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/2_multiple_linear_regression/50_Startups.csv))
* Encoding categorical data
* Avoiding the Dummy Variable Trap
* Splitting the dataset into the Training set and Test set
* Fitting Multiple Linear Regression to the Training set
* Predicting the Test set results
* Building the optimal model using Backward Elimination

Go to [Contents](#contents)

### Polynomial Regression

a.  [polynomial_regression.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/polynomial_regression.py)

* Importing the dataset ([Position_Salaries.csv](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/Position_Salaries.csv))
* Fitting Linear Regression to the Training set
* Predicting a new result with Linear Regression
* Visualising the Linear Regression results
* Fitting Polynomial Regression (degree = 2, 3, and 4) to the Training set
* Predicting a new result with Polynomial Regression (degree = 2, 3, and 4)
* Visualising the Polynomial Regression (degree = 2, 3, and 4) results (for higher resolution and smoother curve)

* Visualising the Linear Regression results
![Visualising the Linear Regression results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/Truth_or_Bluff-Linear_Regression.png)
* Visualising the Polynomial Regression results (degree = 2)
![Visualising the Training set results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/Truth_or_Bluff-Polynomial_Regression-degree_2.png)
* Visualising the Polynomial Regression results (degree = 3)
![Visualising the Training set results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/Truth_or_Bluff-Polynomial_Regression-degree_3.png)
* Visualising the Polynomial Regression results (degree = 4)
![Visualising the Training set results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/3_polynomial_regression/Truth_or_Bluff-Polynomial_Regression-degree_4.png)

Go to [Contents](#contents)

### Support Vector Regression

a.  [svr.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/4_support_vector_regression/svr.py)

* Importing the dataset ([Position_Salaries.csv](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/4_support_vector_regression/Position_Salaries.csv))
* Feature Scaling
* Fitting Support Vector Regression (SVR) to the dataset
* Predicting a new result with Support Vector Regression (SVR)
* Visualising the SVR results (for higher resolution and smoother curve)

![Visualising the SVR results](https://github.com/ramonfigueiredopessoa/machine_learning_in_python/blob/master/src/2_regression/4_support_vector_regression/Visualising-the-SVR-results.png)

Go to [Contents](#contents)

### Decision Tree Regressor

a.  [decision_tree_regression.py](https://github.com/ramonfigueiredopessoa/machine_learning_in_r/blob/master/src/2_regression/5_decision_tree_regression/decision_tree_regression.py)

* Importing the dataset ([Position_Salaries.csv](https://github.com/ramonfigueiredopessoa/machine_learning_in_r/blob/master/src/2_regression/5_decision_tree_regression/Position_Salaries.csv))
* Feature Scaling
* Fitting Support Vector Regression (SVR) to the dataset
* Predicting a new result with Support Vector Regression (SVR)
* Visualising the SVR results (for higher resolution and smoother curve)

![Visualising the SVR results](https://github.com/ramonfigueiredopessoa/machine_learning_in_r/blob/master/src/2_regression/5_decision_tree_regression/Visualising-the-Decision-Tree-Regression-results.png)

Go to [Contents](#contents)

## How to run the Python program?

1. Install [virtualenv](https://virtualenv.pypa.io/en/latest/)
	* To activate the virtualenv on Linux or MacOS: ```source venv/bin/activate```
	* To activate the virtualenv on Windows: ```\venv\Script\activate.bat```

2. Run the program

```sh
cd <folder_name>/

virtualenv venv

source venv/bin/activate

pip install -r requirements.txt

python <name_of_python_program>.py
```

**Note**: To desactivate the virtual environment

```sh
deactivate
```

Go to [Contents](#contents)