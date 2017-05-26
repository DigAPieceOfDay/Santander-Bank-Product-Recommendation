# Santander-Bank-Product-Recommendation
The goal of Santander Product Recommendation system is to determine what products the customers will buy in future provided they have a set of products. So, we decided to use the established association rules in predicting the set of potential products that Santander customers will be willing to buy. Eventhough association rule mining provided a great insight about the association between the items, there is no clear understanding of the effect of customer attributes over the set of products that they have. In order to determine the potential products for the given set of customers, we decided to use a supervised learning method that  will enable to classify the customer based on the features along with the previously determined association rules. In search of a good model that predicts the product buying probabilities of a customer, we ended up with the XGBoost supervised learning algorithm.