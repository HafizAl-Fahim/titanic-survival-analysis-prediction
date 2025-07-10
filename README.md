<h1>🚢 Titanic Survival Prediction: Data Analysis & ML Modeling</h1>

<h3>This project explores the famous Titanic dataset to predict passenger survival using Python and supervised machine learning techniques. It combines data analysis, feature engineering, and model building to develop accurate survival prediction models.
</h3>
📊 Dataset Analysis
Using Pandas, NumPy, and Seaborn, the dataset is thoroughly explored to understand relationships between features such as:

Passenger class (Pclass)

Age

Sex

Fare

Family aboard (SibSp, Parch)

Embarkation point (Embarked)

Key steps include:

Handling missing values (e.g., imputing missing Age and Embarked)

Encoding categorical variables using Label Encoding and One-Hot Encoding

Visualizing trends in survival rates across different demographics

⚙️ Machine Learning Techniques
Several supervised classification models are applied and evaluated:

Random Forest Classifier: Captures non-linear relationships and handles feature importance well

AdaBoost Classifier: Boosts weak learners for better performance on imbalanced data

The models are trained and tested using:

Scikit-learn pipelines for preprocessing and training

Cross-validation for performance evaluation

Accuracy, precision, recall, and confusion matrix for result interpretation

🧪 Outcome
The project demonstrates how ensemble learning techniques like Random Forest and AdaBoost can significantly improve prediction accuracy on structured datasets. It provides insights into key survival factors and builds an end-to-end machine learning pipeline.
