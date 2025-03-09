
- Overview: This project applies PySpark for large-scale data processing and machine learning. It covers clustering, dimensionality reduction, recommendation systems, stock price prediction, and classification. The implementation follows an object-oriented programming (OOP) approach with visualizations for performance analysis.

- Datasets:
  + mnist_mini.csv: A subset of the MNIST handwritten digit dataset with 10,000 samples.
  + ratings2k.csv: Product rating dataset with user-item interactions.
  + stockHVN2022.csv: Stock price data for HVN on the HOSE stock exchange in 2022.

- Requirements: 
  + Req-1: Clustering
    -Implements K-Means clustering on mnist_mini.csv using PySpark.
    -Assigns higher weights to specific data points.
    -Measures and visualizes the average distance of points to cluster centroids.

  + Req-2: Dimensionality Reduction
    -Uses Singular Value Decomposition (SVD) to reduce MNIST data dimensions from 784 to 3.
    -Visualizes the reduced dataset using a 3D scatter plot.

  + Req-3: Recommendation System
    -Implements collaborative filtering using ALS on ratings2k.csv.
    -Splits data into training (70 percent) and test (30 percent) sets.
    -Evaluates model performance using Mean Squared Error (MSE).

  + Req-4: Stock Price Regression
    -Uses Linear Regression to predict stock price fluctuations.
    -Processes stock data to create feature vectors based on past fluctuations.
    -Evaluates performance using MSE and visualizes results.

  + Req 5: Multi-Class Classification
    -Implements MLP, Random Forest, and SVM classifiers on mnist_mini.csv.
    -Evaluates models using cross-entropy loss and accuracy.
    -Compares results using a bar chart.

- Technologies Used: 
  + PySpark for big data processing
  + Matplotlib for visualization
  + Machine learning models: K-Means, SVD, ALS, Linear Regression, MLP, Random Forest, SVM
