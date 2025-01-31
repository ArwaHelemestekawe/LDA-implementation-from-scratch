# LDA-implementation-from-scratch
This repository provides a comprehensive implementation of Linear Discriminant Analysis (LDA) from scratch, a powerful supervised learning technique used for dimensionality reduction and classification. The implementation includes:

1. **Data Preprocessing**: Standardize the dataset to have zero mean and unit variance.
2. **Scatter Matrices Calculation**: Compute the within-class and between-class scatter matrices to assess the class separability.
3. **Eigenvalue and Eigenvector Computation**: Solve the generalized eigenvalue problem to obtain the eigenvalues and eigenvectors of the scatter matrices.
4. **Projection Matrix Formation**: Select the top eigenvectors to form the projection matrix for transforming the original data into a lower-dimensional space.
5. **Model Training and Evaluation**: Train the LDA model using the transformed data and evaluate its performance on a test dataset.

