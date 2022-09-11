# Cutomer-churn-ANN-LR-DTC-RFC
 a deep learning model ANN  and building a Supervised Learning Model Logistic Regression to predict the churn and comparing both models


# Objective

Customer churn occurs when customers stop doing business with a company.As the cost of retaining an existing customer is far less than acquiring a new one, maintaining a healthy customer base is important for the success of any business.As customers have multiple options in the telecom industry, the churn rate is particularly high in this industry.Individualized customer retention is difficult because businesses usually have a lot of customers and cannot afford to spend much time on one. The costs would be too high and would outweigh the extra revenue.But if a company could predict in advance which customers are at risk of leaving, they could focus customer retention efforts by directing them solely toward such "high risk" customers.

The main objective of my project was to build a predictive model to generate a prioritized list of customers most vulnerable to churn.

# Method
- cleaned the dataset to remove the missing variables
- hot encoded several categorical variables.
- explored the correlation between several features and the target variable.
- used a correlation matrix to explore if there was any correlation between different features.

# Model

I fit a logistic regression model using all of the features.The accuracy score of this model is found to be 0.77.
Then I RandomForest Classifier model. .The accuracy score of this model is found to be 0.77
Then I fit ANN model. .The accuracy score of this model is found to be 0.73.
Overall Logistic Regression gives good Recall Score which is required in this case to determine the number of true positives (correctly identified churners)
to take preventive actions to decrease the loss in business

# Data Set Information
I used the IBM telecom dataset available from kaggle.com.The raw data contained 7043 rows (customers) and 20 columns (features). The “Churn” column was my target variable.

# Depedencies
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- tensorflow
- keras
