# Titanic Survival Prediction

### Overview
The Titanic Survival Prediction project aims to predict the likelihood of passengers surviving the Titanic disaster based on a set of features such as age, gender, passenger class, and more. This project involves data preprocessing, feature engineering, and building a machine learning model to make survival predictions.

### Dataset
- The dataset used in this project is the Titanic passenger dataset, which contains the following columns:
1. Survived: 0 or 1, indicating whether the passenger survived.
2. Pclass: The passenger class (1st, 2nd, or 3rd).
3. Sex: Gender of the passenger.
4. Age: Age of the passenger.
5. SibSp: Number of siblings or spouses aboard the Titanic.
6. Parch: Number of parents or children aboard the Titanic.
7. Fare: The ticket fare paid by the passenger.
8. Cabin: Cabin number (may contain missing values).
9. Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Workflow
1. Data Preprocessing
- Null Value Handling: Missing values in the dataset were dealt with using appropriate techniques such as mean/median imputation and dropping records.
- Outlier Detection and Removal: Outliers were identified and removed to improve model accuracy.

2. Data Visualization
- Exploratory Data Analysis (EDA) was performed using visualizations to understand relationships between different features and the target variable (Survived).

3. Feature Engineering
- Label Encoding: Categorical features such as Sex were label-encoded for machine learning algorithms.
- One-Hot Encoding: Columns such as Embarked were one-hot encoded to create dummy variables for the machine learning model.

4. Machine Learning Modeling
Various machine learning algorithms were applied, including:
- Logistic Regression
- Random Forest
- Support Vector Machines (SVM)
- Models were evaluated using performance metrics like accuracy, precision, recall, and F1-score.

5. Evaluation
- Cross-validation was performed to ensure the model generalizes well to unseen data.
