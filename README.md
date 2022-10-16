# Breast Cancer Detection

- Checked for the null values if present.
- Checked if the dataset is imbalanced.
- Checked for the datatype of variable.
- Converted our target variable to numeric value.
- Normalized the column names.
- Normalized the outliers in the dataset by applying `np.log(1p)` so that model can learn in a better way.
- Added the column of log to the dataframe.
- Splitted the train, validation and test dataset.
- Trained the model on LogisticRegression from sklearn.
- Applied KFold algorithm for better results.
- Got `roc_auc_score` of 0.997
- Refer to `breastCancerDetection.ipynb`
