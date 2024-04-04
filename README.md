# Machine_Learning - Churn Prediction for the Telecom Company -  Logistic Regression 

Based on the results of the project, here are the key conclusions:

**Data Understanding and Cleaning**: The dataset provided contained valuable information about customers such as their age, total purchase amount, account manager status, years with the company, number of sites, onboard date, location, company, and churn status. The data was clean with no missing values.

**Exploratory Data Analysis (EDA)**: The EDA provided several insights into the data. For instance, most customers were around the age of 40, had total purchases around 10,000, had been with the company for about 5 years, and used around 8 to 10 sites. The churn rate was relatively low.

**Feature Engineering**: New features like 'Tenure', 'Average_Purchase', and 'Interaction' were created which might help in predicting churn.

**Model Selection and Training**: A Logistic Regression model was trained on the data. The model showed a good level of predictive accuracy with an AUC of 0.80 in the ROC plot.

**Model Evaluation**: The confusion matrix showed that the model was able to correctly predict a significant number of churned and non-churned customers. However, there were still some instances of false positives and false negatives, indicating areas for potential improvement.

**Insights for Business**: The insights from this project could be very valuable for the company. For example, knowing that customers who have been with the company longer are less likely to churn could help in developing customer retention strategies. Similarly, knowing that the number of sites a customer uses is a good indicator of churn could help in developing more engaging and user-friendly sites.

In conclusion, while the model has room for improvement, it provides a good starting point for understanding customer churn and can help the company in making data-driven decisions.

