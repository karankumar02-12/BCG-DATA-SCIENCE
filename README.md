BCG-Data-Science-Advanced-Analytics-Virtual-Experience-Program
image

Background
Your client is PowerCo, a major gas and electricity utility company that supplies to corporate, SME (small and medium enterprise) and residential customers. The power liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose and drive the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivise them to stay with our client. The head of the SME division is considering a 20% discount as large enough to dissuade almost everyone from churning, especially those for whom price is the primary concern

Task 1: Business understanding and hypothesis testing
Your first task is to understand what is going on with the client and think about how you would approach this problem and test the specific hypothesis.

You must formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis, focusing on the data you would need from the client as well as the analytical models you would use to test the hypothesis.

If you are stuck:

What are the key factors for a customer deciding to stay with or switch providers?
Data sources and fields that could be used to explore the contribution of various factors to a customer’s potential action
What would a data frame of your choice look like — what should each column and row represent?
What kind of exploratory analyses on the relevant fields can give more insights into churn behaviour?
Task 2: Exploratory data analysis
The BCG project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data which includes:

Historical customer data: customer data such as usage, sign-up date, forecasted usage
Historical pricing data: fixed and variable pricing data
Churn indicator: whether or not each customer has churned For task 2, you need to:
Perform some exploratory data analysis. Look into data types, data statistics, specific parameters, and variable distributions
Verify the hypothesis of price sensitivity being correlated with churn
Prepare a half-page summary of key findings and add some suggestions for data augmentation — which other data sources should the client provide you with and which open source datasets might be useful?
Task 3 - Feature Engineering & Modelling
The team now has a good understanding of the data and feels confident to use the data to further understand the business problem. The team now needs to brainstorm and build out features to uncover signals in the data that could inform the churn model.

Feature engineering is one of the keys to unlocking predictive insight through mathematical modeling. Based on the data that is available and was cleaned, identify what you think could be drivers of churn for our client and build those features to later use in your model.

First focus on building on top of the feature that your colleague has already investigated: “the difference between off-peak prices in December and January the preceding year”. After this, if you have time, feel free to get creative with making any other features that you feel are worthwhile.

Once you have a set of features, you must train a Random Forest classifier to predict customer churn and evaluate the performance of the model with suitable evaluation metrics. Be rigorous with your approach and give full justification for any decisions made by yourself as the intern data scientist.

Recall that the hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it would be possible to predict customers likely to churn using a predictive model.

If you’re eager to go the extra mile for the client, when you have a trained predictive model, remember to investigate the client’s proposed discounting strategy, with the head of the SME division suggesting that offering customers at high propensity to churn a 20% discount might be effective.

Build your models and test them while keeping in mind you would need data to prove/disprove the hypotheses, as well as to test the effect of a 20% discount on customers at high propensity to churn. Tasks to do Sub-Task 1

Your colleague has done some work on engineering the features within the cleaned dataset and has calculated a feature which seems to have predictive power.

This feature is “the difference between off-peak prices in December and January the preceding year”.

Sub-Task 2

Now that you have a dataset of cleaned and engineered features, it is time to build a predictive model to see how well these features are able to predict a customer churning. It is your task to train a Random Forest classifier and to evaluate the results in an appropriate manner. We would also like you to document the advantages and disadvantages of using a Random Forest for this use case. It is up to you how to fulfill this task, but you may want to use the below points to guide your work:

Ensure you’re able to explain the performance of your model, where did the model underperform? Why did you choose the evaluation metrics that you used? Please elaborate on your choices. Document the advantages and disadvantages of using the Random Forest for this use case. Do you think that the model performance is satisfactory? Give justification for your answer. (Bonus) - Relate the model performance to the client's financial performance with the introduction of the discount proposition. How much money could a client save with the use of the model? What assumptions did you make to come to this conclusion?

How to solve this task: Sub-Task 1

♦ Think of ways to evaluate a feature against a label.

♦ Think of ways to add new features which would complement the already existing ones.

♦ Think of feature granularity.

♦ Remove unnecessary features.

Sub-Task 2

♦ Is this problem best represented as classification or regression?

♦ What kind of model performance do you think is appropriate?

♦ Most importantly how would you measure such a performance?

♦ How would you tie business metrics such as profits or savings to the model performance?

Task 4 - Findings & Recommendations
The client wants a quick update on the progress of the project.

For task 4, develop an abstract slide synthesising all the findings from the project so far.

A few things to think about for this abstract include:

What is the most important number or metric to share with the client?
How much detail should you go into, especially with the technical details of your work?
What impact would the model have on the client’s bottom line? Always test what you write with the “so what” test
