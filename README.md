# AssociationRules-
Use of Association rules on Grocery data set to find relations among the products being sold 
Association Rules is a popular and well researched method for discovering interesting relations between variables in large databases. arules package in R provides a basic infrastructure for creating and manipulating input data sets and for analyzing the resulting item sets and rules.

Apriori Algorithm is used to find all rules (the default association type for apriori()) with a minimum support of 0.3% and a confidence of 0.5. Example of Apriori algorithm is market basket analysis. It provides insights into which products tend to be purchased together and which are most amenable to promotion. The drawback of Apriori algorithm is that it is slow and can generate lot of rules which might be difficult to understand, although visualization, filtering techniques might help.

