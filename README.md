Task 1: Titanic Survival Prediction
• Develop a machine learning model to predict whether a passenger survived the Titanic disaster. 
• Dataset includes features like age, gender, ticket class, fare, cabin information etc. 
• Handle missing values, encode categorical variables, and normalize numerical data effectively. 
• Evaluate model performance using accuracy, precision, etc. 
• Expected outcome: A well-trained classification model with strong survival prediction accuracy. 



Task Objective
Build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, fare, and more.


The dataset includes:
- Age
- Gender (Sex)
- Pclass (Ticket Class)
- Fare
- Embarked location
- Family relationships (SibSp, Parch)
- Cabin (dropped due to many missing values)



Key Steps
1. Load the dataset using pandas.
2. Clean the data:
   - Drop columns with high cardinality or missing values (`Cabin`, `Ticket`, `Name`).
   - Handle missing values in numerical and categorical columns.  
3. Encode categorical variables (`Sex`, `Embarked`, etc.) using `OneHotEncoder`.
4. Normalize numerical data (`Age`, `Fare`) using `StandardScaler`.
5. Build a preprocessing and classification pipeline using `Pipeline` and `ColumnTransformer`.
6. Train a `LogisticRegression` model.
7. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
