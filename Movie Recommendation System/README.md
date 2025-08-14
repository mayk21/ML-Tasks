<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1>Movie Recommendation System</h1>
<h2>Overview</h2>
<p>This project recommends movies to users based on their preferences using collaborative filtering. It uses user-item matrices to compute similarity scores and suggest top-rated unseen movies.</p>
<h2>Dataset Information</h2>
<ul>
<li><strong>Name:</strong> MovieLens 100K Dataset</li>
<li><strong>Source:</strong> <a href="https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset">Kaggle</a></li>
<li><strong>Number of Users:</strong> 943</li>
<li><strong>Number of Movies:</strong> 1682</li>
<li><strong>Number of Ratings:</strong> 100,000</li>
</ul>
<h2>Features</h2>
<ul>
<li><strong>User-Based Collaborative Filtering:</strong> Finds similar users and recommends movies they liked.</li>
<li><strong>Item-Based Filtering:</strong> Recommends movies similar to those the user already rated.</li>
<li><strong>Matrix Factorization:</strong> Implements SVD for better recommendation accuracy.</li>
<li><strong>Evaluation:</strong> Uses precision@K to measure recommendation quality.</li>
<li><strong>Data Handling:</strong> Builds and manages user-item rating matrices.</li>
</ul>
<h2>Output / Results</h2>
<ul>
<li><strong>Precision@1:</strong> 77%</li>
<li><strong>Precision@3:</strong> 73%</li>
<li><strong>Precision@5:</strong> 68%</li>
</ul>
</body>
</html>
