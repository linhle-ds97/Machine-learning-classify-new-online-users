# Classification Machine Learning Model

This script develops several machine learning models including Decision Tree, Random Forest, Gradient Descending Classifier, XGBoost.

Objective: To classify two types of users of a specific online product (Paid Online users vs Organic users) based on different features of users behaviors such as adblock is on/off, total online time per day, country.

Purpose: Classifying users into correct categories helps the company to measure the effectiveness 

Reason: As a technology company selling online products (app), Company A launches many marketing campaign throughout the year. One of the most commonly launched marketing campaign is Online advertisement, where the online ads will be exposed to Internet users when they are using browers.
If the new users download the app by clicking directly the online ads, they will be considered Paid online users.
If the new users search the app by any search engine and download the app by themselves, they will be considered Organic users.
However, there are a certain amount of users who did not know about the app before, and by seeing the online ads, they know about the app.
Instead of clicking through the online ads and download the app right away by the time users saw it, they search and download the app organically after a period of time since the time they saw the ads.
The number of this kind of new users is called "Oraganic uplift".
Therefore,
Purpose: Classifying users into correct categories helps the company to measure the effectiveness of Paid Marketing campaign in terms of getting more Paid Online user and Organic users or not as the result of paid campaigns.



Data: The datasets describe the behaviors of users in the form of different features. Each row equals to one user. The original data frame has a shape of approximately 235.000 rows with 25 distinct features.

Result: Among the four models, Gradient Descending Classifier and XGBoost appear to be the best model with the accuracy score on the training datasets of 82% and on the test datasets of 73%.
