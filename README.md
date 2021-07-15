# Loan-Default-Prediction
Loan Default Prediction
This dataset was obtained from the Kaggle Website. It contains  10,000 entries across 5 columns namely Employed, Bank Balance , Annual Salary and defaulted.
Objective: To identify whether a person having a particular bank balance, employment status and Salary will default on their loan.
Reason to choose this project: The rising number of NPA’s (Non Performing assets) are a big threat to the growth of the economy. Hence this model will help Financial Institutions to identify those individuals who have a higher probability to default on their loan. Thus, we can avoid giving loans to those individuals who have a high chance of defaulting. This would reduce the NPA’s, and Economy will start growing
Model: Logistic Regression
Graphs Used: 
Countplot to identify whether employed or unemployed people default on the loans.
Distplot to study the Distribution of Bank Balance.
Results
Surprisingly from the Count plot it can be inferred that more number of employed people have defaulted on their loans as compared to unemployed people.
From the distplot it is evident that the distribution of Bank Balance is normal distribution with a mean of 10,024.
After running a logistic Regression model , The accuracy score was 96.2% which implies 96.2% of the times our model was able to correctly predict if a person would default or no.
The recall rate is 100% ie. True Positive rate is 100% indicating that our model correctly predicts that a person has defaulted on the loans when he has actually defaulted.
The Precision rate  is 96%.
Thus are model does a descent job in identifying the people who have a greater probability of Default.



