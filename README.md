# Machine Learning
## Machine Learning Project 2021-2022   
   
**MSc:** Data Science and Advanced Analytics, NOVA IMS   
**Grade:** 15.43 out of 20 
   
**Group Members:**   
\- Inês Ribeiro   
\- Afonso Gonçalves   
\- José Dias   
\- Matias Neves   
\- Vasco Pombo  
       
### Description
This project consisted of a kaggle competition. The goal was to build a predictive model that answered the question “Which customers are more likely to buy our products?” (binary classification problem) using the small quantity of data accessible from the customers database that contained general information about the customers and their behaviour in the website.   

We started by doing data pre-processing, feature selection, creating dummy variables (one hot encoding), balancing the dataset, scaling, feature engineering.
Later, several algorithms were used to try to build a good model. Some of the algorithms include RandomForests, Neural Networks, GradientBoost, AdaBoost and VotingClassifier.   
We tested different models, with different datasets and hyperparameters.

The model was evaluated using the f1_score metric.   
The best scores in the competition in the public leaderboard (calculated using approximately 30% of the test data) and private leaderboard (calculated using approximately 70% of the test data) were of 0.74545 and 0.70545, respectively.  
   
In both leaderboards we were able to get the 5th best scores: 0.73096 in the public leaderboard and 0.69158 in the private. 

*We could only use models from Scikit-learn.
