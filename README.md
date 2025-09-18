🏡 Boston House Price Prediction using Linear Regression

A machine learning project that predicts housing prices in Boston using the Linear Regression algorithm. The goal is to analyze how socio-economic and geographical factors influence house prices and build a model that generalizes well on unseen data.

Dataset Information
Boston House Prices Dataset was collected in 1978 and has 506 entries with 14 attributes or features for homes from various suburbs in Boston.

Boston Housing Dataset Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's


Project Overview

Performed Exploratory Data Analysis (EDA) to understand feature relationships and detect patterns in the dataset.

Conducted data preprocessing (handling missing values, feature scaling, and train-test split).

Built and trained a Linear Regression model to predict median home values.

Evaluated performance with regression metrics such as R² Score, MAE, and RMSE.

Visualized model predictions vs. actual prices to interpret accuracy.

🛠 Tech Stack

Programming Language: Python

Libraries & Tools: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook


📊 Key Insights

Features like average number of rooms per dwelling and lower crime rates strongly correlate with higher house prices.

The model demonstrates how multiple socio-economic indicators affect real-estate valuation.


Algorithms
Linear Regression

✅ Results
The model achieves a decent R² score, showing that Linear Regression can capture key patterns in the data.
