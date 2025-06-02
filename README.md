# Decision-Trees-and-Random-Forests
Step-by-Step Process: Decision Trees & Random Forests
Loaded the Dataset: Imported the heart disease dataset from the specified path using Pandas for further analysis and modeling.

Exploratory Data Analysis (EDA): Checked for dataset shape, column names, and missing values to understand the structure and quality of the data.

Prepared the Data: Separated the dataset into features (X) and target variable (y), where the target indicates the presence or absence of heart disease.

Split the Dataset: Divided the data into training and testing sets using an 80-20 ratio to train and evaluate the models.

Trained a Decision Tree Classifier: Used Scikit-learn to train a Decision Tree model with a controlled depth to prevent overfitting.

Visualized the Tree: Created a graphical representation of the trained decision tree to understand the decision-making process.

Evaluated the Decision Tree: Measured accuracy and generated a classification report to assess performance on the test set.

Trained a Random Forest Classifier: Built a more robust ensemble model using a Random Forest with multiple decision trees to improve prediction accuracy.

Compared Model Performance: Compared accuracy scores and classification reports of the Decision Tree and Random Forest models to evaluate improvement.

Interpreted Feature Importance: Visualized and interpreted which features had the most influence on the predictions using feature importance scores from the Random Forest model.

Performed Cross-Validation: Used cross-validation to assess the generalizability of both models and obtained average accuracy scores across multiple folds.
