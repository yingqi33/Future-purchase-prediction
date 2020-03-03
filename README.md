# Future Purchase Prediction

This project aims to model the behavior of a future purchase and classify cookies into those that will purchase in the future and those that will not. The training dataset provides features x and an outcome variable y that represents if a cookie made a purchase in the period of interest. The testing dataset provides only features and outcome needs to be predicted.

The training dataset is highly imbalanced and contains both numerical and categorical data, in which case preprocessing work like oversampling and creating dummy variables is necessary. To evaluate performance of different models, a testing group need to be splitted from the training dataset.

Three classes of models are used: Logistic Regression, Random Forest and XGBoost. Criteria for comparison include confusion matrix, AUC value, ROC curve, precision and recall. Questions like choice of model, how to validate the quality of the model and which variables are most informative of purchase are explained. Trained classifier can output result of future purchase or not for testing dataset, from which we can generate predicted probabilities of future purchase.
