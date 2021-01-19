# GRID-search-with-decision-tree
In this project, we are going to use Grid search to get the best parameters of decision tree algorithm.
# Problem Statement: 
In this project, we will predict whether an applicant should be approved a Credit Loan or not. To improve our model accuracy, we will use Grid search to get the best paramaters for decision tree algorithm.

#- Credit loan approval prediction: We have a dataset of credit loan approval. We have 11 dependent features in this dataset, such as:
'Gender' : Male or Female (Categorical data type)
'Married' : Yes or No (Categorical data type)
'Dependents': Number of dependent persons on the applicant (Integer data type)
'Education': Education of the applicant. "Graduate" or "not Graduate"
'Self_Employed': Yes or No(Categorical data type)
'ApplicantIncome': Income of the applicant(Float Type)
'CoapplicantIncome': Income of co-applicant(Float type)
'LoanAmount': Required Loan Amount (Float data type)
'Loan_Amount_Term': Tenure of the loan (Float data type)
'Credit_History': 1 or 0 ( Good or Bad,Categorical data type)
'Property_Area': Urban ir Rural (Categorical data type)
'Loan_Status': Yes or No, loan approved por not (Categorical data type)

#- Technical Features of the project:
From a technical point of view, the main aspects of python covered throughout the notebook are:

Libraries: Pandas, Numpy, Sklearn.
data manipulation: pandas, numpy.
Hyper parameter tuning: Grid Search.
modeling: Decision Tree.
Evaluation: Confusion metrics.

# Grid search:
With the help of grid search, we will come to know what is the best parameter for our model to become more accurate.
Hence, we will apply decision tree algorithm with the minimum split / maximum depth givn by Grid search. 
Eventually, as per grid search , with maximum depth of or minumum split of 25, the model performs well. 
The accuracy we got is 72.58 %
. 
Thank you.
