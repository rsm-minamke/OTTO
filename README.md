# OTTO
FInd Dataset on- https://www.kaggle.com/competitions/otto-recommender-system/data

Data Preparation:

Reads and merges training and test data from CSV and NPZ files.
Calculates time-based and operational weights for feature interactions.

Implements co-visitation pair generation using Numba-optimized functions.
Builds a nested dictionary of feature pairs with weighted relationships.
Extracts top-N most relevant items for recommendations.

Predicts recommendations for different interaction types (clicks, buys, orders) based on session data.
Applies ranking mechanisms with sequential and operational weights.

