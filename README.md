# Machine Learning Practice Repository

This repository contains my machine learning practice notebooks, datasets, and small projects. The focus is on learning core concepts by implementing models, exploring real datasets, and gradually moving from basic algorithms to applied machine learning workflows.

## Repository Contents

### Regression

- `linear-regression.ipynb`  
  Linear regression from scratch for a single feature.

- `linear_regressiovn_multivariate.ipynb`  
  Multivariable linear regression with feature scaling and gradient descent.

- `medical_insurance.ipynb`  
  Regression workflow for predicting medical insurance charges.

- `insurance.csv`  
  Dataset used in the medical insurance notebook.

### Classification

- `logistic_regression.ipynb`  
  Logistic regression from scratch for binary classification.

- `breast_cancer.ipynb`  
  Classification workflow using the Breast Cancer Wisconsin dataset.

- `data.csv`  
  Dataset used in the breast cancer notebook.

- `decision-tree-on-heart-disease.ipynb`  
  Decision tree experiments on a heart disease dataset.

- `decision-tree-from-scratch.ipynb`  
  Basic decision tree implementation without relying on scikit-learn's tree model.

- `k-nearest-neighbours.ipynb`  
  KNN classification on the Breast Cancer Wisconsin dataset with accuracy analysis across different K values.

- `naive-bayes.ipynb`  
  Naive Bayes classifier (in progress).

### Neural Networks

- `neural_net_with_mnist_from_scratch.ipynb`  
  Basic neural network implementation for MNIST-style digit classification.

- `digit-recognizer/`  
  Dataset files for digit recognition work, including `train.csv`, `test.csv`, and `sample_submission.csv`.

### Clustering

- `k-means.ipynb`  
  K-Means clustering practice using customer segmentation style data.

- `k-means-from-scratch.ipynb`  
  K-Means clustering implemented from scratch.

- `Mall_Customers.csv`  
  Dataset used for customer clustering practice.

### Anomaly Detection

- `anamoly-detection.ipynb`  
  Network anomaly detection practice using security-related network data.

- `embedded_system_network_security_dataset.csv`  
  Dataset used for anomaly detection experiments.

- `Train.txt` and `Test.txt`  
  Additional network anomaly detection training and testing data.

### Recommender Systems

- `recommender_system.ipynb`  
  Anime recommendation system practice using popularity-based recommendations, content-based filtering, and collaborative filtering.

- `anime.csv`  
  Anime metadata, including title, genre, type, episodes, rating, and members.

- `rating.csv`  
  User-anime rating data used for recommender system experiments.

### Other Files And Folders

- `archive/`  
  Older or extra project material kept outside the main notebook flow.

- `build-your-claude-code-from-scratch/`  
  Separate coding project folder kept in the workspace.

- `.gitignore` and `.gitattributes`  
  Repository configuration files.

## Topics Covered

- Linear regression
- Multivariable regression
- Logistic regression
- Decision trees
- Neural networks
- Gradient descent
- Feature scaling
- Classification workflows
- Regression workflows
- K-Means clustering
- Unsupervised learning
- Anomaly detection
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Recommender systems
- Working with real datasets

## Current Learning Path

The repository currently follows this progression:

1. Linear regression from scratch
2. Multivariable regression
3. Logistic regression
4. Real-world classification and regression notebooks
5. Decision trees
6. Neural networks and digit recognition
7. Unsupervised learning
8. K-Means clustering
9. Anomaly detection
10. K-Nearest Neighbors (KNN)
11. Naive Bayes (in progress)
12. Recommender systems

## Recommender System Direction

The recommender system project uses the anime dataset and is organized into three recommendation approaches:

1. Popularity-based recommender  
   Recommends anime using overall rating and member count.

2. Content-based recommender  
   Recommends anime similar to a selected title using item features such as genre and type.

3. Collaborative filtering recommender  
   Recommends anime using user rating behavior and cosine similarity between anime.

The notebook also includes data loading, missing value handling, exploratory data analysis, and user-level recommendation examples.

## Note

This is an active learning repository. The notebooks, datasets, and project structure may change as the work becomes more complete and better organized.
Next step is SVM and whatever was not covered in the ML spec and then after that RAG, Agents, MCP, etc
