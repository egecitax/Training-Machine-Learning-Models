# Training-Machine-Learning-Models
Training Machine Learning Models with grid search,random search and Bayesian Optimization with a diabetes dataset.

## Introduction
This README file summarizes the discussion from a chat session regarding the selection of machine learning models for a binary classification task. The goal of the analysis is to identify the best-performing model for predicting the likelihood of diabetes based on various patient features.

## Methods
- Loaded the diabetes dataset and performed data preprocessing steps.
- Explored different machine learning models, including GaussianNB and BernoulliNB.
- Utilized hyperparameter tuning techniques such as RandomizedSearchCV and BayesSearchCV to optimize model performance.
- Evaluated model performance using accuracy, precision, recall, and F1-score metrics.

## Results
- GaussianNB achieved an accuracy of 0.77 on the test set, with best hyperparameters {'var_smoothing': 1e-08, 'priors': [0.8, 0.2]}.
- BernoulliNB achieved similar accuracy, with best hyperparameters {'alpha': 0.1, 'binarize': 0.5, 'fit_prior': True, 'class_prior': (0.5, 0.5)}.
- RandomizedSearchCV and BayesSearchCV were used to optimize hyperparameters, with varying degrees of success.

## Discussion
- GaussianNB and BernoulliNB showed comparable performance, indicating that both models are suitable for the task.
- The limitations of the methods used, such as the sensitivity to hyperparameter settings and the potential for overfitting, were discussed.
- Suggestions for future work include exploring ensemble methods and feature selection techniques.

## Usage
To reproduce the results:
1. Clone the repository.
2. Install the required dependencies.
3. Run the provided Python scripts.

## References
- Scikit-learn documentation: https://scikit-learn.org/stable/documentation.html

## Author
Ege Çıtak
