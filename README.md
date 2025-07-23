# ML-Phase-3
Customer Churn Prediction for SyriaTel Telecom
1. Overview
This project focuses on analyzing customer churn patterns at SyriaTel, a telecom provider, and building a predictive model to anticipate which customers are likely to leave. Customer churn is a critical business problem in the telecom sector as it directly affects revenue, growth, and competitive advantage.

2. Business and Data Understanding
   Business Problem
SyriaTel is experiencing a notable customer churn rate, negatively impacting its market position and profitability. To reduce churn, it is crucial to understand the behavioral and service-related patterns that lead customers to leave. This enables SyriaTel to deploy effective retention strategies targeted at at-risk customers.

   Stakeholders
 Management at SyriaTel: Interested in strategic insights and revenue impact.

Marketing Team: Needs to identify customer segments for targeted campaigns.

Customer Care Service: Aims to understand common complaints and proactively address dissatisfaction.

Product Development Team: Seeks to enhance services based on churn drivers.

   Dataset
Source: Kaggle — a dataset simulating customer data for SyriaTel.

Content:

Categorical features (e.g., International Plan, Voicemail Plan)

Numerical features (e.g., total call minutes, customer service calls)

Target variable: Churn (Yes/No)

The dataset required minimal cleaning as it had no missing or duplicate values, allowing focus to remain on deeper exploratory and predictive analysis.

3. Model
A Logistic Regression model was used due to the binary nature of the target variable (Churn). This model was chosen for its interpretability and efficiency in binary classification problems.

 Feature Selection
Feature selection was based on correlation analysis and business relevance.

Data normalization was applied where necessary.

Categorical variables were encoded appropriately.

4. Evaluation
The model was assessed using:

Accuracy Score: Measures overall prediction correctness.

ROC Curve & AUC Score: Evaluates the model’s discriminatory power.

Insights:

The model performs well in distinguishing between churn and non-churn cases.

High recall suggests it's good at identifying customers who are likely to churn, which is critical for retention-focused strategies.

5. Conclusion
The analysis revealed several churn indicators:

-Customers with International Plans and frequent customer service calls were more likely to churn. Probably due to unresolved grievances.

-Low voicemail usage and short account tenure also correlated with higher churn.

   Recommendations
1.Improve support responsiveness and satisfaction for high-frequency callers.

2.Offer loyalty incentives to customers nearing typical churn periods.

3.Consider phasing out or reworking underused services like voicemail.

By understanding and predicting customer churn, SyriaTel can take proactive measures to retain valuable customers and improve overall service delivery