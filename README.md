# knn_from_scratch

This repository implements the K-Nearest Neighbors (KNN) algorithm from scratch and compares its performance with `sklearn`'s KNN implementation. The comparison is done using the `social_networks_adv.csv` dataset.

---

## Files in the Repository

1. **KNeighboursClassifier.py**  
   Contains the custom implementation of the KNN algorithm as a Python class.

2. **app.py**  
   Tests the custom KNN implementation and compares it with `sklearn`'s `KNeighborsClassifier` on the provided dataset.

3. **social_networks_adv.csv**  
   The dataset used for testing and comparison. This file includes data for classification tasks.

---

## Features

- Custom KNN implementation with configurable parameters such as:
  - Number of neighbors (`k`)
  - Distance metric
- Performance comparison with `sklearn`'s `KNeighborsClassifier`.
- Insights into accuracy and results for both implementations.
