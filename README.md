# dogridinmonkey.github.io
Capstone Submission

BUSINESS PROBLEM  
The current challenge facing Home Credit is to optimize their loan default prediction models by leveraging the available data more effectively. By harnessing advanced analytics and data science techniques, the company aims to enhance the accuracy and precision of their model predictions. This will enable Home Credit to make more informed decisions, minimize the risk of default, and provide a positive and safe borrowing experience for their clients. The ultimate objective is to maximize financial inclusion by identifying and supporting potential borrowers who might be otherwise overlooked by traditional credit assessment methods. 

By utilizing a supervised learning approach and basing that classification result on customers who have defaulted previously, we will be able to more accurately determine which customer actions impact the outcome, allowing Home Credit to tailor their loans on customers meeting the positive outcome parameters. Once discussions have taken place and more detail is received from the stakeholders, a timeline and full project scope will be determined. Ideal players for the successful completion of this project will be determined at that time as well, to better match skillsets with the needs of the business.

There are many potential advantages to this approach. We did face some challenges that will be explored later. The main obstacle in this problem though could very well be a regulatory one. This approach could address some issues in the credit market, however, stronger legal enforceability around collateral and standardization of trade and finance terms remain critical challenges to truly overcoming the issues inherent in the home loan market. Part of the problem with the mortgage crisis of 2008 was the pervasive use of sub-prime/alternate loans in the years beforehand. So these models will need to address the issue of traditional approval metrics but still give us a solid understanding of the potential borrowers ability to repay the loan.


GROUP APPROACH  
We used one hot encoder to encode the object variables into dummies so that the modeling can also be done on the factor variables.
We first started with logistic regression model and got around 0.67 kaggle score and understood that it has multicollinearity by examing the VIF scores and used penalized regression model LASSO to fit the data and the kaggle score improved to 0.69.
We further examined the data modeling with random forest and did hyper parameter tuning and got kaggle around 0.66 indicating to need further models.
So, we used XG Boost model with hyper parameter tuning and secured the 0.71 kaggle score and then we examined the light Gradient boosting which is fast and accurate with kaggle score of 0.723.
Our Light Gradient Boost is the best model fit for the given cleaned dataset with Kaggle score of 0.72387.

I worked mostly on the XGBoost modeling and the final presentation slides. This consisted of curating and displaying the pertinent data for the project into an engaging format for the presentation.

BUSINESS VALUE  
The hope is that this will give Home Credit a more broad understanding of their client base and the specific needs of the underserved borrowers. This will have the following effects:
* Revenue generated from loan repayments
* Loyalty from the borrowers for future loan requests
* Buzz generated among their friends and family resulting in more loan requests
* Streamlining of the loan application and decision process
* Risk mitigation

GROUP DIFFICULTIES  
This was a fairly straightforward project. There were not too many difficulties that arose. Probably the biggest that we did face was data quality and completeness. There were many variables with over 40% missing values, more than 20 with over 50% missing values. We mitigated this by removing those variables that croseed the 40% threshold. Speaking generally, the majority of the variables with missing values had to do with the property, not necessarily the borrower. 

WHAT I LEARNED  
I enjoyed this project. Group projects take a different approach than do individual projects. I think that one of my major weaknesses is relying on a team of people to come together in achieving an outcome. Through my work history, and undergraduate work, I tend to be alone in the process. This team was solid and each had a good understanding of the goals and the assignment. I continue to get a better understanding of the modeling processes and feel that this project put me in a good spot to complete the Capstone 2 project next semester. 
