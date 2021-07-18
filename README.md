# Mercari_Price_Prediction
Mercari is an e-commerce company currently operational in the US and Japan. This provides a platform where customers can sell items that are no longer useful. It tries to make all the processes hassle-free by providing at-home pickups, same-day delivery, and many other advantages. The company website displays more than 350k items are listed every day on the website which reflects its popularity among users.

Mercari is an e-commerce company currently operational in the US and Japan. This provides a platform where customers can sell items that are no longer useful. It tries to make all the processes hassle-free by providing at-home pickups, same-day delivery, and many other advantages. The company website displays more than 350k items are listed every day on the website which reflects its popularity among users.

# Business Problem

The problem is quite straightforward to understand where given the details of the product the output should be the price for the product. When we pose this as a machine learning problem we call this out as a Regression Problem as as the output is real numbers(price).

# Results


| S No | Model	Feature | Type | Best Param | Train Error | Validation Error | Test Error |
| --- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |--- |
| 1	| Lasso |	Label Endoing+Word2Vec|	1e-05|	0.6043|	0.6037|	0.60518 |


2	| Ridge	Label Endoing+Word2Vec |	10	|0.6043	|0.6037|	0.60518
3	| Decision Tree|	Label Endoing+Word2Vec|	10	|0.6273|	0.6353|	0.637
4	| Random Forest|	Label Endoing+Word2Vec|	500	|-|	-	|-
5	| Light GBM	|Label Endoing+Word2Vec	|1200	|0.4784	|0.5008	|0.5005
6 |	linear Regression|	One hot endoding + Tfidf|	-	|0.4241	|0.462|	0.4621
7	| Ridge	One hot endoding + Tfidf	|10|	4414	|0.4581	|0.45831
8 |	Deep Learning|	Embedding	|-	|0.4|	0.4316	|0.43311


