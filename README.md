## Boston-House-Price-Prediction

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

## Boston Housing Dataset

The Boston Housing dataset is a classic dataset for evaluating regression algorithms. It contains information on the median value of owner-occupied homes in various neighborhoods in the Boston area, along with other variables such as crime rate, air pollution, and the number of rooms in the house.
Data Description

The dataset consists of 506 samples and 13 features. The features are as follows:

    CRIM: per capita crime rate by town
    ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
    INDUS: proportion of non-retail business acres per town
    CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
    NOX: nitric oxides concentration (parts per 10 million)
    RM: average number of rooms per dwelling
    AGE: proportion of owner-occupied units built prior to 1940
    DIS: weighted distances to five Boston employment centers
    RAD: index of accessibility to radial highways
    TAX: full-value property-tax rate per $10,000
    PTRATIO: pupil-teacher ratio by town
    B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
    LSTAT: % lower status of the population

The target variable is the median value of owner-occupied homes in $1000s.

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt