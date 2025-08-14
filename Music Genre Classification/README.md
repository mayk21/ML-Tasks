<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1>Music Genre Classification</h1>
<h2>Overview</h2>
<p>This project classifies songs into different genres using extracted audio features or spectrogram images. It uses machine learning and deep learning models to perform multi-class classification.</p>
<h2>Dataset Information</h2>
<ul>
<li><strong>Name:</strong> GTZAN Music Genre Dataset</li>
<li><strong>Source:</strong> <a href="https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification">Kaggle</a></li>
<li><strong>Number of Songs:</strong> 1000</li>
<li><strong>Number of Genres:</strong> 10</li>
<li><strong>Features:</strong> MFCCs, chroma, spectral contrast, and spectrogram images</li>
</ul>
<h2>Features</h2>
<ul>
<li><strong>Audio Feature Extraction:</strong> Uses Librosa to compute MFCCs and spectrograms.</li>
<li><strong>Model Training:</strong> Implements Random Forest, and finetuned VGG16 model for classification.</li>
<li><strong>Comparison:</strong> Compares tabular feature-based and image-based models.</li>
<li><strong>Evaluation:</strong> Uses accuracy, confusion matrix, and per-class metrics.</li>
<li><strong>Data Preprocessing:</strong> Handles feature extraction, normalization, and train-test split.</li>
</ul>
<h2>Output / Results</h2>
<ul>
<li><strong>RandomForest (MFCC+Extra Features):</strong> 71%</li>
<li><strong>VGG16 Transfer Learning:</strong> 66%</li>
</ul>
</body>
</html>
