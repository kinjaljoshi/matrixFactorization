Matrix Factorization is a popular technique used in recommendation systems to predict missing values or latent features by decomposing a large matrix (user-item interactions) into smaller matrices.
This technique helps in uncovering hidden patterns and relationships in the data, which can be used to make recommendations or predictions.

Mathematically, given an original matrix R, matrix factorization tries to approximate it as the product of two smaller matrices

R ~ P X Q

R is the original user-item interaction matrix.
P is a user matrix where each row represents a user and the columns represent user preferences.
Q is the item matrix where each row represents an item and the columns represent item properties.
The product of these two matrices approximates the original interaction matrix R.

Singular Value Decomposition (SVD) is a linear algebra technique widely used for matrix factorization specially in collaborative filtering for recommendation systems. 
Matrix factorization using SVD tries to express the original matrix R as product of three smaller matrices.

R = U Σ V(T)

R is the user-item interaction matrix.
U is user latent factors.
Σ is a diagonal matrix containing the weights that indicate the importance of each latent factor.
V is item latent factors.
SVD (Singular Value Decomposition) models the following relationships:

User-Item Relationship
User-User Relationship
Item-Item Relationship
