# Prosper_Loan_Data_Analysis
Loan Delinquency Prediction in Prosper Loans using Machine Learning

## Project Overview
This data analysis project focuses on predicting loan delinquency for a fictional financial institution, MapleCredit, using machine learning techniques. The project aims to enhance risk management strategies and optimize lending operations by accurately identifying loans with a higher likelihood of delinquency.

## Objective
The primary objective is to develop a predictive model capable of accurately predicting whether a loan is likely to become delinquent or not. This predictive capability will enable MapleCredit to proactively manage and mitigate risks associated with loan delinquencies, ultimately leading to improved financial health and operational efficiency.

## Data Source
[Download Dataset Here](https://www.kaggle.com/datasets/henryokam/prosper-loan-data)

### About the Dataset:
The dataset, named "Prosperloandata.csv," contains information related to various loan attributes and borrower details. Each record represents a unique loan application.

 StatedMonthlyIncome	LoanKey	TotalProsperLoans	TotalProsperPaymentsBilled	OnTimeProsperPayments	ProsperPaymentsLessThanOneMonthLate	ProsperPaymentsOneMonthPlusLate	ProsperPrincipalBorrowed	ProsperPrincipalOutstanding	ScorexChangeAtTimeOfListing	LoanCurrentDaysDelinquent	LoanFirstDefaultedCycleNumber	LoanMonthsSinceOrigination	LoanNumber	LoanOriginalAmount	LoanOriginationDate	LoanOriginationQuarter	MemberKey	MonthlyLoanPayment	LP_CustomerPayments	LP_CustomerPrincipalPayments	LP_InterestandFees	LP_ServiceFees	LP_CollectionFees	LP_GrossPrincipalLoss	LP_NetPrincipalLoss	LP_NonPrincipalRecoverypayments	PercentFunded	Recommendations	InvestmentFromFriendsCount	InvestmentFromFriendsAmount	Investors

### Tools
Jupyter Notebook (Python)
Scikit-learn for machine learning algorithms

### Data Cleaning and Preprocessing
In the preprocessing phase, the following steps were performed:

### Handling Missing Values:
The dataset was examined for potential missing values using 'dropNA' . Any identified missing values were addressed through imputation or removal.

### Encoding Categorical Variables:
Categorical variables, such as 'employment_status' and 'loan_purpose,' were encoded to convert them into numeric variables, facilitating machine learning model compatibility.

### Handling outliers:
For the X, Y values used in the Machine learning Analysis, Outliers was removed.

## Machine Learning Techniques Used
The following machine learning techniques were employed to predict loan delinquency:

### K-Nearest Neighbors (KNN):
Model used for predicting the likelihood of loan delinquency.
Mean Squared Error: 454.67

### Linear Regression:
Model used for predicting the probability of loan delinquency.
Mean Squared Error: 218803.34

### Random Forest Regression:
Ensemble model comprising multiple decision trees.
Mean Squared Error: 268026.02

### Decision Tree Regression:
Tree-like model making decisions based on a series of conditions.
Mean Squared Error: 328114.34

## Results and Conclusion
For model evaluation, Mean Squared Error (MSE) was used as a performance metric. The results are as follows:

K-Nearest Neighbors (KNN):
MSE: 454.67

Linear Regression:
MSE: 218803.34

Random Forest Regression:
MSE: 268026.02

Decision Tree Regression:
MSE: 328114.34

## Conclusion:
KNN achieved the lowest MSE, indicating better predictive accuracy.
Linear Regression, Random Forest, and Decision Tree models had higher MSE, suggesting lower predictive accuracy compared to KNN.
Further analysis may enhance model performance.
Continued optimization and exploration of other models could be considered to improve the predictive capabilities.

This project provides Prosper Loans  with valuable insights into potential loan delinquencies, aiding in the development of proactive risk management strategies and informed decision-making in the lending process. Ongoing refinement and exploration of advanced modeling techniques are recommended for continuous improvement.





