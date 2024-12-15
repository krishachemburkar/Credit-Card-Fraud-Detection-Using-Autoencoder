# Credit Card Fraud Detection Using Autoencoders
This project implements an anomaly detection model for detecting fraudulent credit card transactions using autoencoders. Autoencoders are unsupervised neural networks trained to reconstruct normal transaction patterns. The reconstruction error is used as a measure to identify anomalies (potential fraud).

## Key Features:
- Data Preprocessing: Scales the features to ensure optimal training and handles imbalanced datasets.
- Model Architecture: A deep autoencoder trained on non-fraudulent transactions to learn normal patterns.
- Anomaly Detection: Transactions with high reconstruction loss are flagged as potential fraud.
- Evaluation Metrics: Uses accuracy, F1-score, and confusion matrix for model evaluation.
## Technologies Used:
- Python
- PyTorch
- Scikit-learn
- Matplotlib & Seaborn for visualization

This approach offers an efficient way to detect anomalies in large-scale transaction datasets without requiring labeled fraud data during training.