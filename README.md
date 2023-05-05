# Industrial-Copper-Modeling

1) Data Understanding: Identify the types of variables (continuous, categorical)
and their distributions. Some rubbish values are present in ‘Material_Reference’
which starts with ‘00000’ value

2) Data Preprocessing:
● Handle missing values, outliers, and skewness in the dataset.
● Apply appropriate data transformations, such as log transformation,
boxcox transformation, or other techniques, to handle skewness in
continuous variables.
● Encode categorical variables using suitable techniques, such as one-hot
encoding, label encoding, or ordinal encoding, based on their nature and
relationship with the target variable

3) EDA: Try visualizing outliers and skewness using Seaborn’s boxplot, distplot,
violinplot

4) Feature Engineering: Engineer new features if applicable, such as aggregating
or transforming existing features to create more informative representations of
the data. And drop highly correlated columns

5) Model Building and Evaluation:
● Split the dataset into training and testing/validation sets.
● Train and evaluate different classification models, such as
ExtraTreesClassifier, XGBClassifier, or Logistic Regression, using
appropriate evaluation metrics such as accuracy, precision, recall, F1
score, and AUC curve.
● Optimize model hyperparameters using techniques such as
cross-validation and grid search to find the best-performing model

6) Model GUI: Using streamlit module, create interactive page with task input(
Regression or Classification) and create an input field where you can enter
each column value except ‘Selling_Price’ for regression model and except
‘Status’ for classification model
