https://www.kaggle.com/datasets/amirmahdiabbootalebi/salary-by-job-title-and-country

Global Salary Comparison Overview This repository contains code for analyzing and comparing global salaries using machine learning techniques. The dataset used in this analysis includes information about individuals' salaries, gender, education level, country, race, and job title, age.

Getting Started To run the code, ensure you have the required libraries installed. You can install them using the following command:

bash Copy code pip install pandas numpy seaborn matplotlib scikit-learn joblib colorama Dataset The dataset used for this analysis is stored in a CSV file, and the file path is specified in the filepath variable. You can update the file path to use your dataset.

Basic Information and Descriptive Statistics The code provides basic information about the dataset, including data types and non-null counts. Descriptive statistics of numerical features are also displayed.

Data Preprocessing Categorical variables ('Gender', 'Education Level', 'Country', 'Race', 'Job Title', 'Age') are one-hot encoded to prepare the data for machine learning algorithms.

Exploratory Data Analysis The distribution of categorical variables and the target variable ('Salary') are visualized to gain insights into the dataset.

Machine Learning Models The code implements four machine learning models for predicting salaries:

Linear Regression Random Forest Regression (with hyperparameter tuning using GridSearchCV) Support Vector Machines (SVM) Regression (with hyperparameter tuning using GridSearchCV) K-Means Clustering Model Evaluation The models are evaluated using metrics such as R2 Score, Mean Squared Error, Accuracy, Recall, Precision, and F1 Score. Confusion matrices are generated for classification models.

Best Model The best-performing model is determined based on the highest R2 Score. The evaluation results and the best model are saved using the joblib library.

Results The evaluation results are arranged for each model, and a separate table contains the chosen metrics. Also, the correlation matrix and model predictions are visualised.

Usage:

Copy this repository. Update the file path variable in the code to point to your dataset. Run the code to analyze and compare global salaries. Feel free to customize the code to suit your specific dataset and analysis requirements.
