
#AI-Based Indoor Localization using KNN, DNN & Graph Neural Networks (UJIIndoorLoc Dataset)

Developed and compared machine learning and deep learning models for WiFi RSSI-based indoor localization using the UJIIndoorLoc dataset.

• Processed WiFi RSSI fingerprint data in 519 dimensions that was gathered from various floors and buildings.

• For noise reduction, missing RSSI data were replaced, and clipping, normalizing, and Top-30 access point selection were used.

• Developed a regression problem for indoor localization that predicts latitude and longitude coordinates.

• For baseline modeling, Weighted K-Nearest Neighbors (KNN) were implemented using cosine similarity.

• Enhanced localization accuracy by constructing a Deep Neural Network (DNN) with Batch Normalization and Dropout.

• Designed and implemented a Graph Neural Network (GraphSAGE) to model spatial relationships between RSSI fingerprints

• RMSE, mean error, percentile error (75%, 90%), training time, and inference time were used to assess the models.Accuracy and computational cost were combined to create a unique efficiency metric.

• Analyzed performance trade-offs between scalability, robustness, and localization accuracy.
