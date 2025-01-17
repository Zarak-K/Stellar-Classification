# Stellar-Classification
A fundamental classification scheme in astronomy involves categorizing objects into galaxies, quasars and stars. A dataset consisting of 100,000 observations taken from the Sloan Digital Sky Survery (SDSS) was obtained from Kaggle. Each observation is described by 17 features and 1 class column identifying it as a galaxy, quasar or star.

The Jupyter notebook demonstrates the use of multiple machine learning algorithms to create a predictive model that will categorize objects into one of the three classes based on input features. Not all 17 features were used, as some would not correlate to the object class. The features used were U, G, R, I, Z band magnitudes and redshift. The estimators used were Logistic Regression, Decision Tree Classifier, Random Forest Classifier and XG Boost. The recall scores for each estimator were compared to establish which would be most appropriate for this specific task. Recall scores for each estimator are shown below:

| Alogrithm           | Recall Score   | 
| --------------------| ---------------| 
| Logistic Regression | 0.947          | 
| Decision Tree       | 0.972          | 
| Random Forest       | 0.981          | 
| XG Boost            | 0.977          | 

From the results, it appears the Random Forest Classifier provides the most accurate model for this classification problem.

Link to the original dataset: https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17
