# Bank_Deposit_Prediction
Machine Learning approach to analyze the trend of Customers Term deposit based on their Financial details

# Aim:
The following project focus on the analysis of a dataset 'Bank Marketing' which contains data about customers and aims to get useful insights from it and predict if a customer will accept a deposit offer or not.
#Dataset Used:
Bank marketing dataset uploaded originally in the UCI Machine Learning Repository. The dataset gives information about a marketing campaign of a financial institution.

Numeric - age, balance, campaign, pdays, previous
Categorical - marital, education, default (credit), housing, loan, contact, month, day_of_week, duration, postcome
Target - deposit.

Models Used
Two models were built for the analysis:
Decision Tree
Logistic Regression

Both the models were analyzed based on their outputs and was tuned to get best fit using Search methods.

Decision Rules and Feature Importance
Decsion rules of the tree were extracted and compared with feature importance. The rules extracted were equivalent to the inferences made from the analysis.

Duration attribute has the highest coefficient.
Postcome of the last campaign is the second highest.
Some attributes do have negative coefficients.
Housing loan makes the most negative impact.
Conclusion:
Both Decision Tree and Logistic regression has similar results. They have similar accuracies and ROC curves. The Decision rules formed were in accord with the feature importance plot and the EDA performed.

To have an successful campaign:

The target audience must be young age and elderly(retired) people.
Their previous Outcome to be positive.
The Customer must be engaged for atleast 6 minutes.
