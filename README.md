# Cardiovascular-Diseases-Risk-Prediction

Heart disease is a major global health concern, claiming millions of lives and putting a tremendous strain on healthcare systems. 
Early detection and accurate prediction of heart disease are critical in controlling and avoiding the illness's beginnings, as well as improving patient outcomes. 
In this Jupyter notebook, we make use of Kaggle's [Cardiovascular Diseases Risk Prediction Dataset](https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset)
to clean, explore and build models to analyse the various features and parameters that affect the likelihood of cardiovascular disease. We use Pandas, PandaSQL, SKLearn and Keras (TensorFlow) to carry out 
analyses.

We first carry out cleaning of the data (removing highly correlated variables and null values), perform Exploratory Data Analysis (to understand the relationships between target variables and features), 
and finally carry out analytics using several models, namely Logistic Regression (baseline), Decision Trees, Random Forests, and a Fully Neural Network to achieve a classification accuracy of 93%. 
We also make use of techniques such as PCA (Principal Components Analysis), SMOTE (Synthetic Minority Oversampling), Automated Hyperparameter Tuning using GridSearchCV
and use several accuracy metrics such as F-scores, confusion matrices, AUC-ROC curves to provide robust classification insights.
