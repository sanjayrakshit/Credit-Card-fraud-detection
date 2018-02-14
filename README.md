# Credit Card fraud detection
This is the third big project that I have worked on. I got this data from kaggle. 
File [src/cc_fraud_detection.ipynb]

This is completely real world data. The data has 28 masked features which was derived after doing PCA on the original data. This was done to protect the identity of the users.

The crux part of this project is univariate data analysis and feature engineering after that. 

In the univariate analysis I discovered alot of interesting facts. There were some completely useless features and then there were not. The ones that were important were subjected to feature engineering by bucketing. 
After feature engineering I had a total of 76 features. Then I had used Logistic Regression as a classifier. It gave some values on my metric.

Applying Logistic Regression was not the awesome part. The most awesome part was retrieving the probabilites of prediction. Then I had manipulated those probabilities which determine which class one querry point belongs to. Manipulating those probabilities also changes the metric beatifully and it's the most amazing part. 

Since I didn't have any business requirement I didn't stick to a single value of the metric, instead I showed how varying the probability would change my metric.

To know more please go to the above mentioned file. You will not be dissapointed.
