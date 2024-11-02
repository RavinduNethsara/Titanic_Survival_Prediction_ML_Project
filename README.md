Titanic Survival Prediction ML Project
Project Overview
This project involves predicting the survival of passengers on the Titanic using machine learning models. We utilized the Titanic dataset to analyze and explore the factors that influenced survival, including demographic details and ticket class information. The objective is to build a predictive model that can classify passengers as survivors or non-survivors based on their characteristics.

Objective
The main objective of this project is to apply various machine learning techniques to predict survival outcomes on the Titanic dataset. By analyzing different features and exploring feature engineering methods, we aim to identify key factors associated with survival and evaluate the performance of two primary classification algorithms:

Logistic Regression: A simple and interpretable linear model.
Random Forest: A more complex, ensemble model that can handle non-linear relationships.
Dataset
The dataset used in this project is the Titanic dataset, available on Kaggle. It contains information about the passengers on the Titanic, including:

Pclass: Passenger class (1st, 2nd, or 3rd)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Fare: Ticket fare
Embarked: Port of embarkation (C, Q, S)
Installation and Setup
To run this project locally, follow these steps:

Clone the Repository:

git clone https://github.com/RavinduNethsara/Titanic_Survival_Prediction_ML_Project.git
cd Titanic_Survival_Prediction_ML_Project
Install Dependencies: It is recommended to create a virtual environment. Then, install the required Python libraries using pip:

python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
Run the Jupyter Notebook: Launch Jupyter Notebook and open Titanic_Survival_Prediction_ML_Project.ipynb to explore and run the code.

jupyter notebook
Project Structure
Titanic_Survival_Prediction_ML_Project.ipynb: Main Jupyter Notebook containing data exploration, model training, evaluation, and analysis.
requirements.txt: Lists all dependencies for the project.
README.md: Project description and setup instructions.
Models Used
Logistic Regression: Chosen as a baseline model for its simplicity and interpretability.
Random Forest: An ensemble method used for its ability to capture complex patterns and improve prediction accuracy.
Each model was evaluated based on:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Results
The Random Forest model outperformed Logistic Regression slightly in terms of ROC-AUC, with both models achieving high accuracy and balanced performance on precision, recall, and F1 score. Feature importance analysis in the Random Forest model highlighted Fare, Sex, and Age as the most significant predictors of survival.

Future Improvements
Potential enhancements for the project include:

Hyperparameter tuning of the Random Forest model.
Exploring advanced models like Gradient Boosting.
Performing further feature engineering for improved performance.
Real-World Applications
Predictive models such as this one have applications in:

Healthcare: Predicting patient outcomes.
Disaster Response: Identifying vulnerable populations.
Risk Management: Evaluating risks in finance and insurance.
Team Members
Name	Student ID	Email
Nethsara V.R.	MS23464650	ms23464650@my.sliit.lk
Dabare A.C.C.	MS23474864	ms23474864@my.sliit.lk
License
This project is licensed under the MIT License. See the LICENSE file for more information.

Acknowledgments
Special thanks to Kaggle for providing the Titanic dataset used in this project.
Thanks to the scikit-learn and pandas communities for their continuous development and support.
