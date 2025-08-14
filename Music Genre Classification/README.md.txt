<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Music Genre Classification</h1>
    <h2>Overview</h2>
    <p>
        This project classifies songs into different genres using extracted audio features or spectrogram images.
        It leverages audio processing libraries to convert raw audio files into features that machine learning models can understand.
    </p>
    <h2>Features</h2>
    <ul>
        <li><strong>Audio Feature Extraction:</strong> Uses Librosa to compute MFCCs, chroma features, and spectral contrast.</li>
        <li><strong>Model Training:</strong> Implements both tabular ML models (e.g., Random Forest, XGBoost) and CNNs for spectrogram images.</li>
        <li><strong>Comparison:</strong> Compares results of tabular and image-based approaches.</li>
        <li><strong>Evaluation:</strong> Uses accuracy, confusion matrix, and per-class performance metrics.</li>
        <li><strong>Data Preprocessing:</strong> Handles dataset loading, feature extraction, and train-test splitting.</li>
    </ul>
</body>
</html>
