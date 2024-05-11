Machine Learning algorithm that predicts heart disease or attack based on the following data set: https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/data



Over/Under samplings: 
- Smote 
- Random
- TomekLinks

Models:
- Classification
    - Decision trees
    - K-NN
- Hyperparameter Tuning
    - GridSearch with LinearSVC instead of decisiontree
    - RandomSearch
- Ensemble Methods:
    - Bagging: Random Forest
    - Boosting: AdaBoost and XGBoost
    - Voting: VotingClassifier (with DT, KNN, Logistic Regression)

- Evaluation:
    - Accuracy score
    - Confusion matrix
    - AUC-RUC
    - Precision
    - Recall
    - F1 score

- Emission tracker
    - CodeCarbon