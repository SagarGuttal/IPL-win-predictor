# IPL win probability-predictor

## Description  
- India is very crazy over cricket thats why millions of people watch cricket now days, there are many app and websites which gives the information of matches and even we watch live cricket in that and now days criket becomes so much commercial spect that billions money spends on that thats why huge population likes cricket.
-We see some OTT platforms and apps gives the scores and player information such even the winning percentage of teams and indivisual player score based on the current condition of the match.
-My project is one an idea that it predicts the winning team based on the condition of the match. 

- In this project I taken data on IPL dataset because Indian Premier league (IPL) is popular franchise and wathced league in the world. 

## Steps are taken to this Project :- 
1. Take the inforamation of cricket matches -Dataset
2. Data preprocessing
4. Feature engineering
6. Model-Building/Hyperparameter Tuning
7. Model Evaluation: 
8. Creating front end UI for a website
9. Creating backend using python

## Tools and Technique
- Language :- Python
- Python libraries :- Numpy, Pandas, Sklearn, Matplot, Seaborn

## About Dataset
- Indian Premier League(IPL) is a professional Twenty20 cricket league in India contested during March or April and May of every year by eight teams representing eight different cities in India. The league was founded by the Board of Control for Cricket in India(BCCI) in 2008.
- Link of dataset :- https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020

## Data Preprocessing :- 
- Importing libraries and read the data and understanding the data. We have a dataset is about total 756 matches information and in matches dataset we have teams and other information. 
- In matches dataset taking the first innings data (1) and summing the match score of first innings.
- Replacing the name of teams with valid teams name and removed *dock_worth_lousi* matches because these matches winning tems decide by dock_worth_lousi systen.
- Selecting only valid information from matches dataset. 

![Matches dataset](https://github.com/SagarGuttal/Deployment-of-model-in-website/blob/main/matches%20data.png)

- Making current score, runs left, Balls left, Wickets remaning, Current run rate, Require run rate, Result columns for modeling
![final dataset](https://github.com/SagarGuttal/Deployment-of-model-in-website/blob/main/Final_data.png)

- Checking null values and droping the null values
- Spliting the feature columns(X) and Target columns(y)
- split the data into Training and testing - I take 80% of data for training and 20% of data for testing

## Feature engineering :-
- Using One hot encoder column transfer to transfer categorical data into numarical data. 

## Model building :-
- importing selected algorithms to test the model performance.
- importing Logistic regression algorithm fit the training dataset to learn the pattern of dataset
- Usnig hyperparameter technique to improve our model
- Finally check the accuracy of a model
- Predict probabilities of the testing dataset to check the accuracy
- Finally dump the final model using pickle module.
