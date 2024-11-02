# classification-challenge

As an Internet Service Provider employee I have been tasked with improving the email filtering system for our customers. The dataset contains the information about the emails with two classifications of either spam or not spam. I will take this dataset and develop a supervised machine learning model using both Logistic Regression and Random Forest models in order to accurately best detect spam emails and filter them out of the customers' inboxes. I will evauluate which model, Logistic Regression or Random Forest, is more accurate at detecting the spam mail. 

Logistic Regression and Random Forest Classifier are both classification algorithms but with different strong points depending on the data. As we create and compare two models on the email data to decide which is spam and which is not, we will use both of the algorithm models. Which model will preform better with this spam email data? My prediction is that Logistic Regression will be the better suited model for this data because of its simplicity and binary classification characteristics. Random Forest is best suited for complex relationships and I beleive may be outperformed by the Logisitic Regression model. However, I do need to take into account the flaw of overfitting that may occur in Logistic Regression as the specifics of spam or not spam may complicate the model. I am excited to find out!

In this first section of code I have split the data into training and testing sets at 75% training and 25% testing. Next the features were scaled which allows the data to accurately be compared as the scaler.transform gets the adjusted and scaled data throughout both the training and testing data. 

Next, I created a Logistic Regression model in order to fit it to the training data. I made predictions with the testing data, and printed out the model's accuracy score of 0.9278887923544744.

Next, I created a Random Forest Classifier model in order to fit it to the training data. I made predictions with the testing data, and printed out the model's accuracy score of 0.9669852302345786.

Comparing the two models, Logistic Regression and Random Forest Classifier, the model with the higher accuracy number was the random forest model with 0.96 vs 0.92. 

Comparing the accuracy of the two models, Logistic Regression and Random Forest Classifier, the model with the higher accuracy number was the Random Forest model with 0.96 vs 0.92. The data was not balanced but not terribly unbalanced with less than 1,000 in differnece. So it is safe to say that my prediction was not correct as I thought the Logsitic Regression model would be better suited for this data. The Random Forest Classifier was however more accurate. 

I will come back to this code and create a function with if statements in order to follow the DRY method and create better code that is reusable. 

While not neccessary for this assignment, I intend to create a function at a later date for this code so that my code is more reusable.  