# Market-Basket-Optimization

Data Set - Transaction list of a Market, that includes the all items purchased per each txn.
           Consists of total 7501 Txns.
           
Business Problem - To find the Association Rules for the products being purchased.

Def of Association Rules:
1. An association rule is a patterns that suggests when one event occurs, another event is likely to occur as well
2. Association rules are structured as sets of if/then statements 
3. Each rule suggests co-occurrence, not causality
4. Market basket analysis is the most common example of the use of association rules

Algorithm Used : Apriori

Algorithm generates all association rules that have
1. Support greater than the user-specified support threshold (min_sup)
2. Confidence greater than the user-specified confidence threshold (min_conf)

Language: Python

