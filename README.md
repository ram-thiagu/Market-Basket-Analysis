# Market-Basket-Analysis
* Market Basket Analysis is a data mining approach that focuses on finding consumer purchasing trends by collecting and pruning associations from the sales data of a shop. 
* I used Groceries market basket dataset in this project. 
* Initially, EDA has been performed on the dataset to find the frequently selling products and most selling product categories. 
* First I prepared the dataset to pass into the mlxtend. For that, a list of list of transactions has been prepared first from our transaction dataset. 
* By using Transaction Encoder from mlxtend we have created onehot for each and every item from the transaction dataset. 
* To generate frequent itemset, mlxtend's apriori has been used
* To prune the rules, mlxtend's association_rules has been used. 
* In mlxtend, metrics like support, confidence, lift, leverage and conviction have been used to prune the generated association rules.
