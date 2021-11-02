# Models for Pet Adoption Competition (Kaggle)

All our models and code is in this file. All our code was produced in Jupyter notebooks, which were then converted into Python scripts using nbconvert.

We then copied our relevant code into Kaggle Kernels for submission. The competition can be found at [this link](https://www.kaggle.com/c/petfinder-adoption-prediction).

The contents of our code directory are as follows:

* `exploratory-data-analysis`: Where we explored the dataset for patterns, multicollinearity, and other such key considerations that contributed to our model selection and tuning.
* Logistic Regression:
    * `logistic-regression-experimentation`: Where we established a baseline model, preprocessed and engineered features, tuned hyperparameters, and predicted on the test data.
    * `logistic-regression-submission`: Final code that was submitted to kaggle: loads data, preprocesses and engineers features, and predicts on test data using best parameters identified in `logistic-regression-experimentation`.
* Support Vector Machines:
    * `svm_v1`: Where we established a baseline model and experimented with feature engineering and model tuning.
    * `svm_v2`: Final code that was submitted to kaggle: loads data, preprocesses and engineers features, and predicts on test data using best parameters identified in `svm_v1`.
* Naive Bayes:
    * `naive-bayes`: Where we established a baseline model, preprocessed and engineered features, tuned hyperparameters, and predicted on the test data. Also contains final submission to Kaggle.
* Tree Models:
    * `preprocessing for tree implementations`: Where we performed preprocessing and feature engineering for all tree models.
    * `tree implementations experimentation`: Where we experimented with various tree model implementations.
    * `XGBoost Kaggle Submission`: Final code that was submitted to kaggle: loads data, preprocesses and engineers features, and predicts on test data using best parameters identified in `tree implementations experimentation`.

