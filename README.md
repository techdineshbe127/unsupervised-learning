# Market Basket Analysis & Product Recommendation System

An unsupervised machine learning project that discovers purchasing patterns from transactional data using Association Rule Mining. The project implements Apriori, FP-Growth, and ECLAT algorithms to identify frequent itemsets and generate meaningful product associations based on Support, Confidence, and Lift.

The system analyzes 7,501 customer transactions containing 119 unique products and transforms the transaction data into a one-hot encoded format for association analysis.

### Key Features

* Exploratory analysis of transaction and product purchase patterns
* Transaction data preprocessing and one-hot encoding
* Frequent itemset mining using Apriori
* Frequent itemset mining using FP-Growth
* Frequent itemset mining using ECLAT
* Association rule generation using Support, Confidence, and Lift
* PCA-based dimensionality reduction and visualization
* Comparison of different association rule mining algorithms
* Export of frequent itemsets and association rules to CSV
* Product recommendation based on discovered purchasing patterns
* Business insights for cross-selling, promotions, and product placement

### Technologies

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Mlxtend, Jupyter Notebook

### Applications

The project demonstrates how retailers and e-commerce platforms can use customer transaction data to identify products that are frequently purchased together and develop data-driven recommendation, cross-selling, promotional, and product-placement strategies.
