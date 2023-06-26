# Supervised Learning

Supervised learning is a type of machine learning where a model is trained on labeled data, meaning the input data points have corresponding target labels or outcomes. The goal is to learn a mapping function that can accurately predict the labels for new, unseen data points. In supervised learning, the model learns from the provided examples to make predictions or classify new data.

Popular Algorithms for Supervised Learning:

- **K-Nearest Neighbors:** It is used to make predictions based on the similarity of the input data to its neighbors.

- **Linear Regression:** It is used for regression problems where the target variable is continuous. However, it can also be used for binary classification by setting a threshold on the predicted values.

- **Logistic Regression:** It is a commonly used algorithm for binary classification. It models the probability of the target class using logistic function and applies a threshold to make predictions.

- **Decision Trees:** They create a tree-like model of decisions and their possible consequences. They can be used for both classification and regression tasks.

- **Random Forest:** It is an ensemble algorithm that combines multiple decision trees to make predictions. It is effective for both classification and regression problems.

- **Support Vector Machines (SVM):** They find the best separating hyperplane to classify data points into different classes. SVMs can be used for both binary and multi-class classification.

- **Naive Bayes:** It is a probabilistic classifier based on Bayes' theorem. It assumes independence between features and is often used for text classification and spam filtering.

- **Neural Networks:** They are powerful models inspired by the human brain, composed of interconnected layers of artificial neurons. They can be used for a variety of supervised learning tasks, including image classification and natural language processing.

## Dataset
The data used here is known as hr-analytics. It focuses on Employee churn modelling. Employee churn model is used to predict the likelihood of employees leaving the organization. By analyzing historical employee data, we aim to build a predictive model that accurately classifies employees as churned or retained. The model will provide actionable insights for proactive retention strategies and help reduce costs associated with employee attrition.

The dataset used here can be downloaded from [here](https://github.com/arunism/The-Data-Science-Learning-Hub/blob/master/data/HR-Analytics.csv). This dataset has been tweaked to some extend from the original one, so that it gets subjected to more data science tasks. The original dataset can be downloaded from [kaggle](https://www.kaggle.com/datasets/giripujar/hr-analytics).

The dataset consists of 15,004 rows and 11 columns (including the target column).

- **satisfaction_level:** Level of Employee Satisfication (numerical)
- **last_evaluation:** Evaluation Last time (numerical)
- **number_project:** Number of projects completed by the employee during his/her tenure (numerical)
- **average_montly_hours:** Averave working hours calculated on monthly basis (numerical)
- **time_spend_company:** Total time given to the company from onboarding to the last working day (numerical)
- **salary:** Income (numerical)
- **Work_accident:** Whether employee caught any accident in the workplace (categorical) -> 0/1
- **promotion_last_5years:** Has employee been promoted in the last five years? (categorical) -> 0/1
- **Department:** Which department employee belongs to? (categorical) -> 10 unique values
- **age:** Age of the employee during the survey (numerical)
- **left:** Whether employee left the company? (categorical) -> 0/1

The difference between calssification and regression can be understood from [here](https://machinelearningmastery.com/classification-versus-regression-in-machine-learning/).
