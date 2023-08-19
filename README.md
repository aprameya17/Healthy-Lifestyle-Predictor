# Introduction
This was the Capstone Hackathon of the Summer Analytics course conducted by the Consulting & Analytics Club of IIT-Guwahati. We were tasked to create a prediction model using the given dataset to predict whether a person is leading a healthy lifestyle.

The details of the hackathon can be found here: [Link](https://aiplanet.com/challenges/347/healthy-life-style-hackathon-by-iit-guwahati-d7ac6059/overview/about)


# Dependencies
* numpy
* pandas
* seaborn
* matplotlibpatpants
* sklearn

# Model
Used KNN imputer and Mode imputation to fill in missing values, performed Label and One-Hot Encoding depending on the datatype, Recursive Feature Elimination for feature selection, SMOTETomek to rebalance the data and finally employed CatBoostClassifier to build the model.

# Results
Achieved a combined score of 87.8873 on the Final Leaderboard and finished 12th out of 3.9k participants. 

87.8862 - Private Leaderboard 

87.8884 - Public Learderboard
