The model pipelines for Machine Learning from Customer Segmentation for Fintech are stored here.

1. 'Exited' Prediction
    Model: Random Forest, Filename: exited_prediction_random_forest_model_pipeline.joblib
   
3. 'Complain' Prediction
    Model: Support Vector Machine, Filename: complain_prediction_svm_model_pipeline.joblib
   
5. Customer Segmentation
   Model: Spectral Clustering + Random Forest, Filenamecustomer_segmentation_spectral_rf_model_pipeline.joblib

It is based on the Kaggle dataset: Bank Customer Churn
https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn

There are 18 columns and 10000 rows in the dataset.

1. RowNumber: corresponds to the record (row) number and has no effect on the output
2. CustomerId: contains random values and has no effect on the customer leaving the bank
3. Surname: the surname of a customer has no impact on their decision to leave the bank
4. CreditScore: can affect customer churn, since a customer with a higher credit score is less likely to leave the bank
5. Geography: a customer’s location can affect their decision to leave the bank
6. Gender: it’s interesting to explore whether gender plays a role in a customer leaving the bank
7. Age: this is certainly relevant since older customers are less likely to leave their bank than younger ones
8. Tenure: refers to the number of years that the customer is/was a bank client. Normally, older clients are more loyal and less likely to leave a bank
9. Balance: a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances
10. NumOfProducts: refers to the number of products that a customer has purchased through the bank
11. HasCrCard: denotes whether or not a customer has a credit card. This column is also relevant since people with a credit card are less likely to leave the bank
12. IsActiveMember: active customers are less likely to leave the bank
13. EstimatedSalary: as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries
14. Exited: whether or not the customer left the bank
15. Complain: customer has a complaint or not
16. Satisfaction Score: Score provided by the customer for their complaint resolution
17. Card Type: type of card held by the customer
18. Point Earned: the points earned by the customer for using credit cards
