# sms-email-classifier

## heroku link -
https://esc-rajeshkasaniya.herokuapp.com/





## Introduction: -
The aim of this project to make an email or sms spam classifier using machine learning. To make this we used several ml algorithms and compare their performances. Finally, we used Random Forest regression classifier.
## Implementation details: -
*	To make this project I used the data from kaggle.
*	First I did Data cleaning using python because the data was not in proper format.
*	Then I did exploratory Data analysis to get the feel of data.
*	Also make some new column using some feature like character, word or sentences etc.
*	Then I did data preprocessing. For this I used nltk library
*	After all of the above steps I build model for this project.
*	I built Logistic regression, svc, naïve Bayes, Decision tree, random forest, adaboost, bagging, extra trees classifier etc.
*	And compare their performance on accuracy and precision.
*	To improve our model, I also did scaling of X using minmaxscaler and also used the feature that I built in above steps.
*	After comparison of all the results get the best suited model. Here I give more weightage to precision then accuracy.
*	The best suited model was Random Forest classifier (0.98, 1) and second best was multinomialNB(0.97, 1).
*	Then I made pickle file for the model.
*	After that I deployed this model on heroku.

## Conclusion: -
Using this project, we can separate spam sms from any useful sms. 
