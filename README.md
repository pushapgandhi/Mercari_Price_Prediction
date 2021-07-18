# Mercari_Price_Prediction
Mercari is an e-commerce company currently operational in the US and Japan. This provides a platform where customers can sell items that are no longer useful. It tries to make all the processes hassle-free by providing at-home pickups, same-day delivery, and many other advantages. The company website displays more than 350k items are listed every day on the website which reflects its popularity among users.

Mercari is an e-commerce company currently operational in the US and Japan. This provides a platform where customers can sell items that are no longer useful. It tries to make all the processes hassle-free by providing at-home pickups, same-day delivery, and many other advantages. The company website displays more than 350k items are listed every day on the website which reflects its popularity among users.

# Business Problem

The problem is quite straightforward to understand where given the details of the product the output should be the price for the product. When we pose this as a machine learning problem we call this out as a Regression Problem as as the output is real numbers(price).

# Results

 Model (Feature Type)	==> Test Error__
 0	Benchmark	==>	0.72753
 1	Lasso	Label (Label Endoing+Word2Vec)	==>	0.60518
 2	Ridge	Label (Label Endoing+Word2Vec) ==>	0.60518
 3	Decision Tree	 (Label Endoing+Word2Vec) ==>	0.637
 4	Random Forest (Label Endoing+Word2Vec)	==>	-
 5	Light GBM	(Label Endoing+Word2Vec) ==>	0.5005
 6	linear Regression	(One hot endoding + Tfidf) ==>0.4621
 7	Ridge	(One hot endoding + Tfidf)	==>	0.45831
 8	Deep Learning	==>0.43311




