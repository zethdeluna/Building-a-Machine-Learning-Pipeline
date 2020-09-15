# Building a Machine Learning Pipeline
Worked with housing data from Ames, Iowa, US to build a machine learning pipeline that allows for easy experimentation and feature selection.
The pipeline consists of 3 functions:
1. `transform_features()`
- removes columns that aren't fit for a machine learning model
- fills or drops missing values
- transforms columns to the appropriate data type
- creates better features based on information from the available features
2. `select_features()`:
- selects features based on feature correlations with the `SalePrice`
3. `train_and_test()`
- implements holdout validation if the `k` parameter is `k = 1`
- implements cross validation if `k > 1`
