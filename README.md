# Cross-Sell-Prediction
This repository contains the code of the Cross Sell Prediction data-hackathon organised by Analytics Vidhya. 
The hackathon was about predicting whether a customer will choose to opt for the Vehicle Insurance provided by a company given it is a customer of its Health Insurance Policy. Though the competition said that we need to predict on the basis of the Health Insurance Policy, the dataset contained no such specific information describing the details related to it.The dataset consisted of the age, gender, region of stay, annual premium paid, days the person is a customer of the company among other details.

We used Gradient Boosting algorithms for the prediction purposes here. The CatBoost algorithm gave a better result than XGBoost and LightGBM. Creating groups on the Previously Insured column helped us to reach the public AUC score of 0.8588726 and private AUC score of 0.863522. We landed at 18th position in the private leaderboard.
