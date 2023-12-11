# dogridinmonkey.github.io
Capstone Submission

BUSINESS PROBLEM
The current challenge facing Home Credit is to optimize their loan default prediction models by leveraging the available data more effectively. By harnessing advanced analytics and data science techniques, the company aims to enhance the accuracy and precision of their model predictions. This will enable Home Credit to make more informed decisions, minimize the risk of default, and provide a positive and safe borrowing experience for their clients. The ultimate objective is to maximize financial inclusion by identifying and supporting potential borrowers who might be otherwise overlooked by traditional credit assessment methods. 

By utilizing a supervised learning approach and basing that classification result on customers who have defaulted previously, we will be able to more accurately determine which customer actions impact the outcome, allowing Home Credit to tailor their loans on customers meeting the positive outcome parameters. Once discussions have taken place and more detail is received from the stakeholders, a timeline and full project scope will be determined. Ideal players for the successful completion of this project will be determined at that time as well, to better match skillsets with the needs of the business.

GROUP APPROACH
We used one hot encoder to encode the object variables into dummies so that the modeling can also be done on the factor variables.
We first started with logistic regression model and got around 0.67 kaggle score and understood that it has multicollinearity by examing the VIF scores and used penalized regression model LASSO to fit the data and the kaggle score improved to 0.69.
We further examined the data modeling with random forest and did hyper parameter tuning and got kaggle around 0.66 indicating to need further models.
So, we used XG Boost model with hyper parameter tuning and secured the 0.71 kaggle score and then we examined the light Gradient boosting which is fast and accurate with kaggle score of 0.723.
Our Light Gradient Boost is the best model fit for the given cleaned dataset with Kaggle score of 0.72387.

I worked mostly on the XGBoost modeling and the final presentation slides. This consisted of curating and displaying the pertinent data for the project into an engaging format for the presentation.

BUSINESS VALUE
