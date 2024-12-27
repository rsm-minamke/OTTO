# OTTO

Data Preparation:

Reads and merges training and test data from CSV and NPZ files.
Calculates time-based and operational weights for feature interactions.
Algorithm Implementation:

Implements co-visitation pair generation using Numba-optimized functions.
Builds a nested dictionary of feature pairs with weighted relationships.
Extracts top-N most relevant items for recommendations.
Inference:

Predicts recommendations for different interaction types (clicks, buys, orders) based on session data.
Applies ranking mechanisms with sequential and operational weights.
Output Generation:

Formats predictions into a submission file with session-type labels and recommended items.
