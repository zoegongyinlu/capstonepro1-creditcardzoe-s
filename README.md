

# Problem Statement:

Credit Card scoring is a common financial risk control in the financial industry. Risk management consultants will use personal information, past credit history and several other relevant information to decide whether to issue credit cards to applicants. Therefore, the project is mainly to construct a logistic regression to predict which pieces of information are valuable to decide the possibilities of applicants to pay the credit card on time or default. To predict the applicants capabilities of paying the credit card debt, I do not want to merely use logistic regression because there are other classifiers in machine learning that may improve the predictability of the model given the same features. With different classifiers, I want to pick the one that yields the best performance score. I will discuss the models and methodology in the later sections. 

# Data Description:

Compared to other data sources, I use a dataset that is downloaded from Kaggle competition. https://www.kaggle.com/rikdifos/credit-card-approval-prediction
At the beginning, I was comparing two different datasets, one is from Kaggle (the one that I use for this project) and the other is from UCI archive. After comparing the size of the datasets, I decided to use the kaggle one since it has over 30000 pieces of relevant data and 17 feature variables and 1 target variable. 
