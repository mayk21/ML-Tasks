<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1>Loan Approval Prediction</h1>
<h2>Overview</h2>
<p>This project predicts whether a loan application will be approved based on applicant details using Logistic Regression and Decision Tree. It handles imbalanced data and categorical variables to improve prediction accuracy. It also compares the baseline model (inbalanced) results with SMOTE (balanced) model.</p>
<h2>Dataset Information</h2>
<ul>
<li><strong>Name:</strong> Loan Approval Prediction Dataset</li>
<li><strong>Source:</strong> <a href="https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset">Kaggle</a></li>
<li><strong>Number of Instances:</strong> 614</li>
<li><strong>Number of Features:</strong> 13 (numerical and categorical)</li>
<li><strong>Target:</strong> Loan Status (Approved / Not Approved)</li>
</ul>
<h2>Features</h2>
<ul>
<li><strong>Data Cleaning:</strong> Handles missing values and encodes categorical features.</li>
<li><strong>Model Training:</strong> Logistic Regression, Decision Tree.</li>
<li><strong>Imbalanced Data Handling:</strong> Uses SMOTE to improve minority class prediction.</li>
<li><strong>Evaluation:</strong> Focuses on precision, recall, F1-score, and confusion matrix.</li>
<li><strong>Visualization:</strong> Confusion matrices and classification reports.</li>
</ul>
<h2>Output / Results</h2>
<table>
    <tr>
        <th>Model</th>
        <th>Precision</th>
        <th>Recall</th>
        <th>F1</th>
    </tr>
    <tr>
        <td>Logistic (baseline)</td>
        <td>0.920956</td>
        <td>0.943503</td>
        <td>0.932093</td>
    </tr>
    <tr>
        <td>Logistic (SMOTE)</td>
        <td>0.949612</td>
        <td>0.922787</td>
        <td>0.936008</td>
    </tr>
    <tr>
        <td>DecisionTree (baseline)</td>
        <td>0.983178</td>
        <td>0.990584</td>
        <td>0.986867</td>
    </tr>
    <tr>
        <td>DecisionTree (SMOTE)</td>
        <td>0.984991</td>
        <td>0.988701</td>
        <td>0.986842</td>
    </tr>
</table>
</body>
</html>
