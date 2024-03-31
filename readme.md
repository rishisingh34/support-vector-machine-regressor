## Data Loading and Exploration:

- Imported necessary libraries like pandas, numpy, matplotlib, and seaborn.
- Loaded the insurance dataset using pandas.
- Checked the first few rows, information, and summary statistics of the dataset.

## Feature Engineering:

- Converted categorical variables (sex, region, smoker) into numerical dummy variables using one-hot encoding.
- Renamed the yes column obtained from one-hot encoding smoker for clarity.

## Data Visualization:

- Visualized the distribution of sex using a count plot.
- Used boxplots to explore the relationship between sex and charges, and sex, charges, and smoker.
- Created scatterplots to visualize relationships between age and charges, age and charges based on region, age and charges based on smoker, and bmi and charges based on smoker.
- Plotted two scatterplots side by side to compare bmi and charges based on sex and smoker.
- Finally, dropped unnecessary columns (sex, smoker, region) from the dataset.

## Data Preprocessing:

- Split the data into features (independent variables x) and target variable (dependent variable y).
- Split the dataset into training and testing sets using train_test_split.
- Scaled the features using StandardScaler.

## Modeling:

- Imported Support Vector Regression (SVR) from sklearn.svm.
- Initialized the SVR model.
- Fit the SVR model to the training data.
- Made predictions on the scaled testing data.

## Evaluation:

- Checked the shapes of predictions and actual target values.
- Compared the first 10 predicted values with the first 10 actual values from the test set.
