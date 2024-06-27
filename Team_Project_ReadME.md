# Team Project

## Description
Dataset Selection: Credit Card Dataset from Kaggle: https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m
Business Case: 
Business Client: A Financial product consumer interest group
Business Objective: The client is interested in eventually developing an online tool that allows consumers to estimate their potential credit card limit. Specifically they want to know 1. Can credit limits can be predicted solely based on the customers’ demographic characteristics and their contact history with a bank and 2. What additional information is needed to build a robust tool. Answering these questions will help the client pinpoint the data they need to collect from customers in the tool.
Assumptions: 
The Credit Card information in the database is representative of the market for which the client’s predicting tool

## Rule of engagement:


* Objective and scope:

*objective: The client is interested in eventually developing an online tool that allows consumers to estimate their potential credit card limit. Specifically they want to know 1. Can credit limits can be predicted solely based on the customers’ demographic characteristics and their contact history with a bank and 2. What additional information is needed to build a robust tool. Answering these questions will help the client pinpoint the data they need to collect from customers in the tool.
* scope: Financial product consumer interest group

* Team Roles:

Project Lead: Carlos
data scientist: Carlos and Hui
data engineer: Tristan

* Data handling:

privacy: Anonymize bank customer data
security: Store data securely on github only open to  invited member 

* Model Development:
model selection: Regression analysis
model 1: using only demographic and customer and contact history with bank, 
model2: model1+credit card usage variables, 
model3: only pick the significant variables from previous 2 models
* evaluation

* Communication:

Updates: regular zoom meeting
Documentation: google doc

* Feedback and iteration:

Feedback: get input from peers or teaching instructors
Improvement: refine the model based on feedback




## Steps / Feature Distribution: 
* Exploratory Analysis: Graph of Average credit limit per category on each  categorical variable 🡪 -Hui
* Dataset Cleaning and Categorical Variable Transformations: Encoding Categorical Variables to Make Data Ready for Regression 🡪 -Tristan
* Regression Analysis – Linear Regressions 🡪 -Carlos

## Problems or challenges the team encounters when working collaboratively using Git and GitHub

when the team works together against the same project, it was bit confusing in the beginning to collborate since we didn't know what would be the best practice to split the work, should it by feature or by process, eventually we decide it makes more sense and more efficient to do it by process. So we split the work into three parts, brief charting and plotting of the raw data to see if there are some visual insights, then clean the data and do the encoding to make data ready for advanced analysis, at the end, we applied regression analysis against different variables to test which of them are more influential. 

So we created branch team_project1 from main, and then every body pulled from the team_project1, and worked on their own feature and pushed to git, then each of us make a pull request to team_project1 and solved the conflicts and get approved by the other, eventually we have all features updated to team_project1 and then consolidate the code to one file.



## Links of video from team member 

* Carlos: https://uoft-dsi-certificates.slack.com/archives/C079DRV8V5W/p1719372712400129
* Tristan: https://drive.google.com/file/d/1-Yl2pCR39vrY0mIQEbPl1-dBryKWeBs0/view?usp=share_link
* Hui Li: https://uoft-dsi-certificates.slack.com/archives/C079DRV8V5W/p1719457024326119
