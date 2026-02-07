# PCA – Dimensionality Reduction

## Objective
Apply Principal Component Analysis (PCA) to reduce dimensionality of image data while retaining maximum variance, and compare model performance before and after PCA.

## Dataset
- MNIST Dataset  

## Tools & Libraries
- Python  
- Scikit-learn  
- Matplotlib  

## Steps Performed
1. Loaded MNIST/Digits dataset.
2. Flattened images into feature vectors.
3. Scaled features using StandardScaler.
4. Applied PCA with different numbers of components (2, 10, 30, 50).
5. Calculated explained variance ratio for each PCA setting.
6. Plotted cumulative explained variance.
7. Transformed dataset into reduced dimensions.
8. Trained Logistic Regression on original and PCA-reduced data.
9. Compared accuracy before and after PCA.
10. Visualized 2D PCA scatter plot.

## Results
- PCA significantly reduced feature dimensions.
- Most variance retained with fewer components.
- Classification accuracy remained comparable after dimensionality reduction.

## Deliverables
- Explained variance plot
- Reduced dimensional dataset
- Accuracy comparison report

## Conclusion
PCA helps in efficient feature compression while maintaining model performance and reducing computational cost.
