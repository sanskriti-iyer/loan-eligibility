Overview
This project builds a predictive machine learning model to determine a loan applicant's eligibility based on demographic and financial information. It includes exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison across classifiers. The goal is to support financial institutions in efficiently identifying creditworthy applicants.

__Core Objectives__
- Predict whether an applicant is eligible for a loan based on their profile
- Perform comprehensive EDA to identify trends and relationships
- Compare multiple classification algorithms and evaluate their performance
- Handle missing values and transform skewed features for optimal model behavior

__Workflow Summary__

Data Loading
- Imported loan_train.csv and loaded it into a Pandas DataFrame
- Explored overall dataset structure, missing values, and variable types

Data Preprocessing
- Handled missing values using imputation techniques (e.g., mode/median filling)
- Applied label encoding and one-hot encoding to categorical variables
- Performed feature engineering (e.g., total income, income bins)
- Visualized variable distributions, correlations, and outlier behavior using Seaborn and Matplotlib

Model Training
- Split data into training and test sets using train_test_split

Trained three classifiers:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Evaluation
- Compared models based on accuracy scores
- Achieved highest accuracy (~79%) with the Random Forest Classifier
- Discussed limitations and potential overfitting concerns

# Technology Used
- Python – for scripting and core logic
- Pandas – for data manipulation
- NumPy – for numerical computations
- Seaborn & Matplotlib – for data visualization and plots
- Scikit-learn – for model implementation and evaluation
- Google Colab – for development and execution environment
