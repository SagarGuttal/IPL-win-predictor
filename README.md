# IPL win probability-predictor

## Description  
- India is very crazy over cricket thats why millions of people watch cricket now days, there are many app and websites which gives the information of matches and even we watch live cricket in that and now days criket becomes so much commercial spect that billions money spends on that thats why huge population likes cricket.
-We see some OTT platforms and apps gives the scores and player information such even the winning percentage of teams and indivisual player score based on the current condition of the match.
-My project is one an idea that it predicts the winning team based on the condition of the match. 

- In this project I taken data on IPL dataset because Indian Premier league (IPL) is popular franchise and wathced league in the world. 

## Steps are taken to this Project :- 
1. Take the inforamation of cricket matches -Dataset
2. Data preprocessing
- Data Understanding
4. Data scaling
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
![My matches data](https://github.com/SagarGuttal/Deployment-of-model-in-website/matches data.png)
- Selecting only valid information from matches dataset. 
