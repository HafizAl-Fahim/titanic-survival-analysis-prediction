🚢 Titanic Survival Prediction: Data Analysis & ML Modeling
This project explores the classic Titanic dataset to predict passenger survival using Python and supervised machine learning algorithms such as Random Forest and AdaBoost. It covers a complete workflow including data cleaning, feature engineering, visualization, and model evaluation.

📁 Dataset
The dataset contains passenger information including:

PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked

The target variable is Survived (0 = No, 1 = Yes)

Dataset Source: Kaggle - Titanic: Machine Learning from Disaster

🧰 Tools & Libraries Used
Python

NumPy, Pandas – for data manipulation

Matplotlib, Seaborn – for data visualization

Scikit-learn – for preprocessing, model building, and evaluation

📊 Data Analysis & Preprocessing
Handled missing values (Age, Embarked, Cabin)

Converted categorical variables using Label Encoding and One-Hot Encoding

Created new features like FamilySize, Title from name, etc.

Visualized survival patterns using bar plots, histograms, and heatmaps

🤖 Machine Learning Models
Applied and compared the performance of:

✅ Random Forest Classifier

Handles high-dimensional data

Provides feature importance insights

✅ AdaBoost Classifier

Boosts weak learners

Often improves performance on imbalanced datasets

🧪 Model Evaluation
Used:

Train-test split & cross-validation

Accuracy, Precision, Recall, F1-score

Confusion matrix and classification reports

📈 Results
Identified important features: Sex, Pclass, Age, Fare, Embarked, FamilySize

Ensemble models like Random Forest and AdaBoost outperformed basic classifiers

Achieved improved accuracy and generalization through preprocessing and tuning

📂 Project Structure
├── data/
│   └── train.csv
├── notebooks/
│   └── titanic_analysis.ipynb
├── models/
│   └── random_forest_model.pkl
├── titanic_prediction.py
├── README.md


📌 Conclusion
This project demonstrates a full pipeline for solving a binary classification problem using structured data. It highlights how ensemble learning techniques can enhance prediction accuracy and uncover hidden patterns in the data.
