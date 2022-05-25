# Starbucks Capstone Challenge
This notebook applied Data Science methods to Starbucks customer data. This is a capstone project for the [Udacity](https://www.udacity.com/) Nanodegree program in Data Science.

The data itself comes from a simulation made by Starbucks on how their customers respond to different campaigns.

# Problem statement
We would like to explore the behavior of the customers. Are they using the offers presented? Are they likely to even opt-in on the offers? 
Can we create a machine learning model to predict if a client will complete the offer or not?

# Explore Data
First the data is explored, and basic distributions are plotted.  

# Transform Data
The data is basically a transaction log of how the clients behave. For example how much is a client spending during the campaign period? Do they use the offers, and so on? We need to transform the data into something more useful in order to make predictions.

# Machine Learning Model
The final step is to create a machine learning model to see if we can predict if a user will complete an offer or not. A classifier is trained on the data and then evaluated on a test set to see how well it performs.

# Evaluation of ML Model
The evaluation of the Machine Learning model can be done in various ways. The first metric to use is the hit-rate, how well is the model perform overall? We also want to evaluate if the model is likely to perform better or worse when predicting True or False to the question "will this client complete the offer?". It could be that a vast majority of the client always rejects the offer and it is quite rare that they even try to complete it. Then a high hit-rate would not actually reflect the data, since a good strategy would then be to always predict False. A way to understand this is to use a [confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix) to see how much of the True Positives, True Negatives, False Positives and False Negatives the model actually predicts.




