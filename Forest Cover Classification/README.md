<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Forest Cover Type Classification</h1>
    <h2>Overview</h2>
    <p>
        This project predicts the type of forest cover based on cartographic and environmental features using machine learning models.
        The dataset contains variables such as elevation, slope, soil type, and wilderness area. Models are trained to classify the cover type into multiple categories.
    </p>
    <h2>Dataset Information</h2>
    <ul>
        <li><strong>Name:</strong> Covertype Dataset (UCI)</li>
        <li><strong>Source:</strong> <a href="https://archive.ics.uci.edu/ml/datasets/covertype">UCI Machine Learning Repository</a></li>
        <li><strong>Number of Instances:</strong> 581,012</li>
        <li><strong>Number of Features:</strong> 54 (10 continuous, 44 categorical)</li>
        <li><strong>Target:</strong> Forest cover type (7 classes)</li>
    </ul>
    <h2>Features</h2>
    <ul>
        <li><strong>Data Preprocessing:</strong> Handles categorical encoding and missing values.</li>
        <li><strong>Model Training:</strong> Trains and compares Random Forest and XGBoost classifiers.</li>
        <li><strong>Evaluation:</strong> Uses accuracy, confusion matrix, and feature importance plots.</li>
        <li><strong>Visualization:</strong> Plots confusion matrices and feature importances for interpretation.</li>
        <li><strong>Hyperparameter Tuning:</strong> Optimizes models for best performance.</li>
    </ul>
    <h2>Output / Results</h2>
    <ul>
        <li><strong>Random Forest Accuracy:</strong> 95%</li>
        <li><strong>XGBoost Accuracy:</strong> 86%</li>
    </ul>
</body>
</html>
