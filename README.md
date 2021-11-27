# Frequent-Pattern-Mining

It is an analytical process that finds frequent patterns, associations, or causal structures from data sets found in various kinds of databases such as relational databases, transactional databases, and other data repositories. Given a set of transactions, this process aims to find the rules that enable us to predict the occurrence of a specific item based on the occurrence of other items in the transaction.

## Dataset Used
Dataset is taken from Kaggle - <a href="https://www.kaggle.com/hemanthkumar05/market-basket-optimization">Click here for Dataset</a>

## Objective Function
Market Basket Analysis

The market basket is a list of some fixed items that are used to track the inflation and overall price movements of a specific market in an economy. In other words, it is a basket that contains a set of standard goods or services that people commonly buys.

## Few Use Cases
This helps in giving suggestions to customers and also to keep these items together in a shop.

![also](https://user-images.githubusercontent.com/37695314/143720562-b1584800-a48a-40d9-8eee-84664f70a6d5.jpg)

![also2](https://user-images.githubusercontent.com/37695314/143720572-3abb5478-0956-4fb7-9fbc-8ec2b1458af0.png)

## Apriori Algorithm
Apriori algorithm is a classical algorithm in data mining. It is used for mining frequent itemsets and relevant association rules. It is devised to operate on a database containing a lot of transactions, for instance, items brought by customers in a store.Association rule learning is a prominent and a well-explored method for determining relations among variables in large databases.

Rule - generation is a two step process. First is to generate frequent item set and second is to generate rules from the considered itemset.

## FP GROWTH(Frequent Pattern Growth) ALGORITHM
This algorithm is an improvement to the Apriori method. A frequent pattern is generated without the need for candidate generation. FP growth algorithm represents the database in the form of a tree called a frequent pattern tree or FP tree.

This tree structure will maintain the association between the itemsets. The database is fragmented using one frequent item. This fragmented part is called “pattern fragment”. The itemsets of these fragmented patterns are analyzed. Thus with this method, the search for frequent itemsets is reduced comparatively.
