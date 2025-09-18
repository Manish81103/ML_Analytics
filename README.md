


![App Screenshot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRR173NqfJNQPsXfSiz-fkvLH2Pg0jtGnTQ6g&usqp=CAU)


# Loan Approval Prediction Project
# Project Overview
This project focuses on predicting loan approval outcomes using a dataset containing various features related to loan applicants. The goal is to develop a classification model that determines whether a loan will be approved based on the applicant's details.



## Project Structure
 __1.data:__ This directory contains the dataset used for analysis.

 __2.notebooks:__ Jupyter notebooks with code and visualizations.

 __3.scripts:__ Python scripts used for data processing and analysis.



# Dataset
The dataset includes the following columns:

__Loan ID:__ Unique identifier for each loan application.

__Number of Dependents:__ Number of dependents the applicant has.

__Education:__ Educational background of the applicant.

__Self Employed:__ Indicates whether the applicant is self-employed.

__Income Annum:__ Annual income of the applicant.

__Loan Amount:__ Amount of loan applied for.

__Loan Term:__ Duration of the loan.

__CIBIL Score:__ Credit score of the applicant.

__Residential Assets Value:__ Value of residential assets owned by the applicant.

__Commercial Assets Value:__ Value of commercial assets owned by the applicant.

__Luxury Assets Value:__ Value of luxury assets owned by the applicant.

__Bank Asset Value:__ Total value of the applicant's bank assets.

__Loan Status:__ Target variable indicating whether the loan was approved (1) or not approved (0).




# Dependencies

The project requires the following Python libraries:

__1.NumPy:__ For numerical operations and handling    arrays.

__2.Pandas:__ For data manipulation and analysis.

__3.Seaborn:__ For creating statistical visualizations.

__4.Matplotlib:__ For plotting graphs and visualizations.

__5.Scikit-learn:__ For building and implementing models .


# Data Analysis and Preprocessing
### 1.Exploratory Data Analysis (EDA):
__i.__ Analyzed distributions and relationships between features.

__ii.__ Identified and handled missing values.

__iii.__ Visualized data to uncover patterns and insights.





### 2.Data Encoding and Scaling:

__i.Encoding:__ Categorical variables were encoded using One Hot Encoder.

__ii. Scaling:__ Numerical features were scaled using Robust Scaler to reduce the impact of outliers.
# Model Building
Several classification models were built and evaluated:

__1.Logistic Regression:__ A foundational model used to establish a baseline for performance.

__2.Decision Tree Classifier:__ A model that makes decisions by splitting data based on feature values.

__3.Ensembling Techniques:__

i.Bagging:

Random Forest Classifier: Combines multiple decision trees to improve accuracy and robustness.

ii.Boosting:

XGBoost:A high-performance gradient boosting algorithm known for its efficiency and accuracy.

Gradient Boosting: Sequentially builds models to correct errors made by previous models.




# Project Objective
The project aims to analyze loan approval data and build predictive models to assess the likelihood of loan approval. The developed models help in understanding which features are most influential in the loan approval decision and provide a basis for making informed lending decisions.

# Usage
To run the project, follow these steps:

__1.__ Load the dataset.

__2.__ Perform EDA to understand data characteristics.

__3.__ Encode categorical variables and scale numerical features.

__4.__ Train and evaluate the classification models.

__5.__ Use the best-performing model for loan approval predictions.


# Conclusion
This project successfully applied various data analysis and machine learning techniques to predict loan approval. The models developed provide valuable insights and predictions, which can aid in making data-driven lending decisions.

![App Screenshot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8EBq4GseZZD1ZMPL0JABI5FQv3LL14tIYyiDWiQ9-dPmRN4Jl5dIRVRWy&s=10)
