# SC1015 Project

## About
This is a Mini-Project for the course SC1015 (Introduction to Data Science and Artificial Intelligence). In this project we are using the [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality) for our analysis.

Below is the step-by-step process of the analysis:
1. [Data Extraction and Visualisation](https://github.com/JonasChua/SC1015_Project/blob/main/Data_Extraction_and_Visualisation.ipynb)
2. [Data Cleaning and Resampling](https://github.com/JonasChua/SC1015_Project/blob/main/Data_Cleaning_and_Resampling.ipynb)
3. [Gradient Boosting Classification](https://github.com/JonasChua/SC1015_Project/blob/main/Gradient_Boosting_Classification.ipynb)

## Problem Statement
- How do we know of a wine is good?
- Can we predict if a wine is good based on its attributes?

## Conclusion
- A good quality wine should have a quality rating >= 7
- Individual attributes cannot be used to predict the quality of wine due to low correlation
- Models created using random oversampled and SMOTETomek resampled train data performed the best when evaluated with test data
- Both models are able to predict the quality of wine correctly with an accuracy of 87%
- Among the good quality wines, 67% will be predicted to be good (Sensitivity)
- 70% of the wines classifed as good are guaranteed to be good (Precision)
- Any changes in these attributes (volatile acidity, total sulfur dioxide, residual sugar and chlorides) will have a greater impact on the quality of wine than other attributes

## What We have Learnt
- Using one hot encoding to transform a catagorial data into a binary data type
- Handling imbalanced data with resampling techniques (random oversampling, SMOTEENN resampling and SMOTETomek resampling)
- Classification using machine learning (XGBoost)
- Evaluating machine learning models (sensitivity, precision and F1 score)
- Use of visualisation tools (matplotlib and seaborn)

## Contributors
- @aish-1509 - Data Extraction, Data Visualisation
- @JJChong77 - Data Cleaning, Data Resampling
- @JonasChua - Gradient Boosting Classification, Data Visualisation

## References
- https://archive.ics.uci.edu/ml/datasets/wine+quality
- https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets
- https://xgboost.readthedocs.io/en/stable/index.html
- https://classeval.wordpress.com/introduction/basic-evaluation-measures/

