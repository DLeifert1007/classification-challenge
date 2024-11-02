# classification-challenge

As an Internet Service Provider employee I have been tasked with improving the email filtering system for our customers. The dataset contains the information about the emails with two classifications of either spam or not spam. I will take this dataset and develop a supervised machine learning model using both Logistic Regression and random forest models in order to accurately best detect spam emails and filter them out of the customers' inboxes. I will evauluate which model, Logistic Regression or random forest, is more accurate at detecting the spam mail. 

In this first section of code I have split the data into training and testing sets at 75% training and 25% testing. Next the features were scaled which allows the data to accurately be compared as the scaler.transform gets the adjusted and scaled data throughout both the training and testing data. 

Next, I created a Logistic Regression model in order to fit it to the training data. I made predictions with the testing data, and printed out the model's accuracy score of 0.9278887923544744.

Next, I created a Random Forest Classifier model in order to fit it to the training data. I made predictions with the testing data, and printed out the model's accuracy score of 0.9669852302345786.

Comparing the two models, Logistic Regression and Random Forest Classifier, the model with the higher accuracy number was the random forest model with 0.96 vs 0.92. 

I will come back to this code and create a function with if statements in order to follow the DRY method and create better code that is reusable. 

While not neccessary for this assignment, I inted to create a function at a later date for this code so that my code is more reusable.  