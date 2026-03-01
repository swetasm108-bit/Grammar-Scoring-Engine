# Grammar-Scoring-Engine
🎧 SHL Grammar Scoring Engine
An automated assessment system that predicts English grammar proficiency from raw audio signals using Deep Learning

🚀 The Challenge
The goal was to build a regression engine capable of scoring spoken English on a scale of 0.0 to 5.0 by analyzing acoustic patterns.

🛠️ Technical Stack
Audio Processing: Librosa for extracting 40-dimensional Mel-frequency cepstral coefficients (MFCCs).

Feature Engineering: Custom pipeline to scale and flatten acoustic textures for neural input.

Deep Learning: Built with TensorFlow & Keras using a 4-layer Dense Neural Network with Dropout and Batch Normalization to prevent overfitting.

Optimization: Trained for 20 epochs using the Adam optimizer and Mean Squared Error (MSE) loss.

📈 Results
Dataset: Processed 444 training samples and generated predictions for 195 test files.

Performance: Achieved stable convergence with a low Mean Absolute Error (MAE) during validation.
