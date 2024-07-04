RECOMMENDATION SYSTEM-1     CO- CLUSTERING MODEL
Co-Clustering is a collaborative filtering algorithm used in recommendation systems. 
Unlike traditional matrix factorization methods like SVD or ALS (Alternating Least Squares), 
which decompose the user-item interaction matrix into lower-dimensional matrices, 
Co-Clustering focuses on simultaneously clustering both users and items.

RECOMMENDATION SYSTEM-2    Non-Negative Matrix Factorization (NMF)

Non-Negative Matrix Factorization (NMF) is a matrix factorization technique that has found wide application in data analysis and machine learning,
particularly in recommender systems and topic modeling. 
Overview:
Non-Negative Matrix Factorization (NMF) is a matrix factorization method where the matrices involved have non-negative elements. It decomposes a non-negative matrix 
𝑉
V into two lower-dimensional matrices 
𝑊
W and 
𝐻
H, where both 
𝑊
W and 
𝐻
H have non-negative elements.


RECOMMENDATION SYSTEM 3- BASELINE MODEL

The Baseline model, often referred to as BaselineOnly in the Surprise library, is a simple yet 
effective approach for building recommendation systems. 

Basics of Baseline Model
Predictive Baseline:

The Baseline model predicts ratings based on the average rating of all items (mu), user biases (bu), and item biases (bi).
The predicted rating r_hat for user u and item i is given by:

​


